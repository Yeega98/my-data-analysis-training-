# my-data-analysis-training-
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Exercises\n",
    "\n",
    "Answer the questions or complete the tasks outlined in bold below, use the specific method described if applicable."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** What is 7 to the power of 4?**"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2401"
      ]
     },
     "execution_count": 1,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Split this string:**\n",
    "\n",
    "    s = \"Hi there Sam!\"\n",
    "    \n",
    "**into a list. **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['Hi', 'there', 'dad!']"
      ]
     },
     "execution_count": 3,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Given the variables:**\n",
    "\n",
    "    planet = \"Earth\"\n",
    "    diameter = 12742\n",
    "\n",
    "** Use .format() to print the following string: **\n",
    "\n",
    "    The diameter of Earth is 12742 kilometers."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "planet = \"Earth\"\n",
    "diameter = 12742"
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
      "The diameter of Earth is 12742 kilometers.\n"
     ]
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Given this nested list, use indexing to grab the word \"hello\" **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "lst = [1,2,[3,4],[5,[100,200,['hello']],23,11],1,7]"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hello'"
      ]
     },
     "execution_count": 14,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Given this nested dictionary grab the word \"hello\". Be prepared, this will be annoying/tricky **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "metadata": {},
   "outputs": [],
   "source": [
    "d = {'k1':[1,2,3,{'tricky':['oh','man','inception',{'target':[1,2,3,'hello']}]}]}"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'hello'"
      ]
     },
     "execution_count": 22,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** What is the main difference between a tuple and a list? **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "# Tuple is immutable"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Create a function that grabs the email website domain from a string in the form: **\n",
    "\n",
    "    user@domain.com\n",
    "    \n",
    "**So for example, passing \"user@domain.com\" would return: domain.com**"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'domain.com'"
      ]
     },
     "execution_count": 26,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "domainGet('user@domain.com')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Create a basic function that returns True if the word 'dog' is contained in the input string. Don't worry about edge cases like a punctuation being attached to the word dog, but do account for capitalization. **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 27,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "True"
      ]
     },
     "execution_count": 28,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "findDog('Is there a dog here?')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Create a function that counts the number of times the word \"dog\" occurs in a string. Again ignore edge cases. **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 30,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "2"
      ]
     },
     "execution_count": 31,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "countDog('This dog runs faster than the other dog dude!')"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "** Use lambda expressions and the filter() function to filter out words from a list that don't start with the letter 's'. For example:**\n",
    "\n",
    "    seq = ['soup','dog','salad','cat','great']\n",
    "\n",
    "**should be filtered down to:**\n",
    "\n",
    "    ['soup','salad']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 34,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "seq = ['soup','dog','salad','cat','great']"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "['soup', 'salad']"
      ]
     },
     "execution_count": 35,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": []
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Final Problem\n",
    "**You are driving a little too fast, and a police officer stops you. Write a function\n",
    "  to return one of 3 possible results: \"No ticket\", \"Small ticket\", or \"Big Ticket\". \n",
    "  If your speed is 60 or less, the result is \"No Ticket\". If speed is between 61 \n",
    "  and 80 inclusive, the result is \"Small Ticket\". If speed is 81 or more, the result is \"Big    Ticket\". Unless it is your birthday (encoded as a boolean value in the parameters of the function) -- on your birthday, your speed can be 5 higher in all \n",
    "  cases. **"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {
    "collapsed": true
   },
   "outputs": [],
   "source": [
    "def caught_speeding(speed, is_birthday):\n",
    "    pass"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Small Ticket'"
      ]
     },
     "execution_count": 42,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "caught_speeding(81,True)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 43,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "'Big Ticket'"
      ]
     },
     "execution_count": 43,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "caught_speeding(81,False)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Great job!"
   ]
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
   "version": "3.8.11"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 1
}
