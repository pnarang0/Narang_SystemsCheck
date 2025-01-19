{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "07b533f8-181b-4a1a-b785-df06f3de9fde",
   "metadata": {},
   "source": [
    "# Systems Check\n",
    "## Course Goals\n",
    "### Expectations\n",
    "\n",
    "**What I hope to get out of this class:**\n",
    "- Gain a deeper understanding of Python programming\n",
    "- Learn how to apply Python to real-world data problems\n",
    "- Develop teamwork and collaboration skills\n",
    "\n",
    "\n",
    "![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "b4e21e3d-c5e6-46dc-a9ed-773b341ae83a",
   "metadata": {},
   "outputs": [],
   "source": [
    "# Variable assignment\n",
    "\n",
    "a = 10\n",
    "b = 20"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "2d9d4382-d3fb-477a-89a8-57b4e78b4624",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "# for loop\n",
    "\n",
    "for i in range(1,6):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "30ad9093-6016-4905-9d20-6ac2ccddc7d1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Name Puneet Narang\n",
      "Your Welcome Puneet Narang\n"
     ]
    }
   ],
   "source": [
    "# a function with a print statement and a return statement\n",
    "\n",
    "def intro(name):\n",
    "    print(\"Name\",name)\n",
    "    return f\"Your Welcome {name}\"\n",
    "\n",
    "message = intro(\"Puneet Narang\")\n",
    "print(message)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "377cb73f-f564-4480-94f7-fae3ab02bcce",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
