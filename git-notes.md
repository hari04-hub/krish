print("Hello, World!")

full\_name='Bairam Hari Krishna'

age = 25

bank\_balance=343.22

is\_male= True

print(type(full\_name))

print(type(age))

print(type(bank\_balance))

print(type(is\_male))

print(full\_name)

print(age)

print(bank\_balance)

print(is\_male)

print("completed successfully")



family = \['hari','vamshi','kiran','manga','mani','sweety']

print(family\[3])

family.append('krishna')

print(family)


//list contains dictaniers
family=[
    {
        'father_name' : 'bairam damodhar',
        'mother_name' : 'manga',
        'brother_name' : 'vishnu',
        'work' :[
            {
                'father' : 'farmer',
                'mother' : 'house wife',
                'brother' : 'aeo'
            }
            ,
            {
                'father_age':45,
                'mother_age':40,
                'brother_age':28
            }
        ]
    },
    {
        'father_name':'reddy',
        'mother_name':'aruna',
        'son' : 'mani',
        'daughter':'sannihitha',
        'work':[
            {
                'father':'farming',
                'mother':'house',
                'son':'manager',
                'daughter':'mba'
            }
            ,
            {
                'father_age':46,
                'mother_age':40,
                'son':27,
                'daughter':25
            }
        ]
    }
]
print(family[0]['father_name'])
print(family[0]['work'][0]['brother'])
print(family[1]['work'][0]['daughter'])











