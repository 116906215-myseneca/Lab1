# Lab1
Lab 1 repository

import datetime

def calculate_age():

    birth_year = int(input("Enter your birth year: "))
    
    current_year = datetime.datetime.now().year
    
    age = current_year - birth_year
    
    return age
