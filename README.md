# Python-Basic-codes
These are basic python codes
import datetime
class user:
   """user is a class which can store user data
that can save millions of user data"""
 def __init__(self, full_name, birthday):
     """stores the values of users
     """
     self.full_name = full_name
     self.birthday = birthday #yyyymmdd

     def age(self):
     """return the age of the user"""
     today =datetime.date(2018,10,14)
     yyyy = int(self.birthday[0:4])
     mm = int(self.birthday[4:6])
     dd= int(self.birthday[6:8])

     dob = datetime.date(yyyy,mm,dd) #dob
     age_in_days = age_in_days
     age_in_years = age_in_days/360
     return int(age_in_years)

user("Pradeep Gedara", "19890603")
print(user.age())
