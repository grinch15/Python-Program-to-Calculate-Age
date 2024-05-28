from datetime import date


def age(birthdate):
    today = date.today()
    age = today.year - birthdate.year - \
        ((today.month, today.day) < (birthdate.month, birthdate.day))
    return age


birthdate = date(1996, 2, 27)

print(f"With birth date of {birthdate}, you are {age(birthdate)} years old")
