{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The sum of is 7\n"
     ]
    }
   ],
   "source": [
    "num1 = int(input(\"Enter the first number: \"))\n",
    "num2 = int(input(\"Enter the second number: \"))\n",
    "sum = num1 + num2\n",
    "print(\"The sum of is\", sum)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "My favorite animal is: horse\n"
     ]
    }
   ],
   "source": [
    "Animal=input(\"Favorite animal:\")\n",
    "print(\"My favorite animal is:\",Animal)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Temperature will be: 3.0F = -16.11111111111111C\n"
     ]
    }
   ],
   "source": [
    "Fahrenheit = float(input(\"Enter temperature in Fahrenheit: \"))\n",
    "Celsius = (Fahrenheit - 32) * 5.0/9.0\n",
    "print(f\"Temperature will be: {Fahrenheit}F = {Celsius}C\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The perimeter of a triangle is 9.0\n"
     ]
    }
   ],
   "source": [
    "a = float(input(\"Length of a: \"))\n",
    "b = float(input(\"Length of b: \"))\n",
    "c = float(input(\"Length of c: \"))\n",
    "\n",
    "perimeter = a + b + c\n",
    "\n",
    "print(\"The perimeter of a triangle is\", perimeter)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6.0 squared will be 36.0\n"
     ]
    }
   ],
   "source": [
    "number = float(input(\"Enter a number to see the square: \"))\n",
    "square = number**2\n",
    "print(f\"{number} squared will be {square}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[2, 4, 6, 8, 12]\n"
     ]
    }
   ],
   "source": [
    "group = [2, 4, 6, 8, 10, 12]\n",
    "group.remove(10)\n",
    "print(group)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[5, 7, 3, 8, 4, 6]\n"
     ]
    }
   ],
   "source": [
    "list1 = [5, 7, 3]\n",
    "list2 = [8, 4, 6]\n",
    "list1.extend(list2)\n",
    "print(list1)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "New list: [10, 20, 40]\n",
      "Cancelled item: 30\n"
     ]
    }
   ],
   "source": [
    "items = [10, 20, 30, 40]\n",
    "removed_item = items.pop(2)\n",
    "print(\"New list:\", items)\n",
    "print(\"Cancelled item:\", removed_item)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The index of 'green' is 2\n"
     ]
    }
   ],
   "source": [
    "colors = ['red', 'blue', 'green', 'yellow']\n",
    "index = colors.index('green')\n",
    "print(\"The index of 'green' is\", index)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6\n"
     ]
    }
   ],
   "source": [
    "def get_last_element(lst):\n",
    "    print(lst[-1])\n",
    "\n",
    "list_a = [0, 2, 4, 6]\n",
    "get_last_element(list_a)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The list will be : ['5', '3', '6', '1', '9', '5']\n"
     ]
    }
   ],
   "source": [
    "user_list = []\n",
    "while True:\n",
    "    a = input(\"Enter a value: \")\n",
    "    if a == \"\":\n",
    "        break\n",
    "    user_list.append(a)\n",
    "print(\"The list will be :\", user_list)"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
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
   "version": "3.12.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
