import time
import random

points = 0
european_countries = [
    "Albania", "Andorra", "Armenia", "Austria", "Azerbaijan", "Belarus", "Belgium",
    "Bosnia and Herzegovina", "Bulgaria", "Croatia", "Cyprus", "Czech Republic",
    "Denmark", "Estonia", "Finland", "France", "Georgia", "Germany", "Greece",
    "Hungary", "Iceland", "Ireland", "Italy", "Kazakhstan", "Kosovo", "Latvia",
    "Liechtenstein", "Lithuania", "Luxembourg", "Malta", "Moldova", "Monaco",
    "Montenegro", "Netherlands", "North Macedonia", "Norway", "Poland", "Portugal",
    "Romania", "San Marino", "Serbia", "Slovakia", "Slovenia", "Spain",
    "Sweden", "Switzerland", "Turkey", "Ukraine", "United Kingdom", "Vatican City"
]
asia_countries = [
    "Afghanistan", "Armenia", "Azerbaijan", "Bahrain", "Bangladesh", "Bhutan", "Brunei",
    "Cambodia", "China", "Cyprus", "Georgia", "India", "Indonesia", "Iran", "Iraq",
    "Japan", "Jordan", "Kazakhstan", "Kuwait", "Kyrgyzstan", "Laos", "Lebanon", "Malaysia",
    "Maldives", "Mongolia", "Myanmar (Burma)", "Nepal", "North Korea", "Oman", "Pakistan",
    "Palestine", "Philippines", "Qatar", "Saudi Arabia", "Singapore", "South Korea",
    "Sri Lanka", "Syria", "Taiwan", "Tajikistan", "Thailand", "Timor-Leste", "Turkey",
    "Turkmenistan", "United Arab Emirates", "Uzbekistan", "Russia", "Vietnam", "Yemen"
]
oceania_countries = [
    "Australia", "Fiji", "Kiribati", "Marshall Islands", "Micronesia", "Nauru", "New Zealand",
    "Palau", "Papua New Guinea", "Samoa", "Solomon Islands", "Tonga", "Tuvalu", "Vanuatu",
    "East Timor (Timor-Leste)"
]
african_countries = [
    "Algeria", "Angola", "Benin", "Botswana", "Burkina Faso", "Burundi", "Cabo Verde", "Cameroon",
    "Central African Republic", "Chad", "Comoros", "Democratic Republic of the Congo", "Djibouti",
    "Egypt", "Equatorial Guinea", "Eritrea", "Eswatini", "Ethiopia", "Gabon", "Gambia", "Ghana",
    "Guinea", "Guinea-Bissau", "Ivory Coast", "Kenya", "Lesotho", "Liberia", "Libya", "Madagascar",
    "Malawi", "Mali", "Mauritania", "Mauritius", "Morocco", "Mozambique", "Namibia", "Niger",
    "Nigeria", "Rwanda", "Sao Tome and Principe", "Senegal", "Seychelles", "Sierra Leone",
    "Somalia", "South Africa", "South Sudan", "Sudan", "Tanzania", "Togo", "Tunisia", "Uganda",
    "Zambia", "Zimbabwe"
]
north_american_countries = [
    "Antigua and Barbuda", "Bahamas", "Barbados", "Belize", "Canada", "Costa Rica", "Cuba",
    "Dominica", "Dominican Republic", "El Salvador", "Grenada", "Guatemala", "Haiti", "Honduras",
    "Jamaica", "Mexico", "Nicaragua", "Panama", "Saint Kitts and Nevis", "Saint Lucia",
    "Saint Vincent and the Grenadines", "Trinidad and Tobago", "United States"
]
south_american_countries = [
    "Argentina", "Bolivia", "Brazil", "Chile", "Colombia", "Ecuador", "Guyana", "Paraguay",
    "Peru", "Suriname", "Uruguay", "Venezuela"
]

print("Welcome to my geography game!\n ")
time.sleep(2)
name=input("What is your name? ")

all_countries = (
    european_countries
    + asia_countries
    + oceania_countries
    + african_countries
    + north_american_countries
    + south_american_countries
)

while True:
    time.sleep(1)
    print("                                  ")
    random_country = random.choice(all_countries)

    continent = None

    if random_country in asia_countries:
        continent = "Asia"
    elif random_country in european_countries:
        continent = "Europe"
    elif random_country in oceania_countries:
        continent = "Oceania"
    elif random_country in african_countries:
        continent = "Africa"
    elif random_country in north_american_countries:
        continent = "North America"
    elif random_country in south_american_countries:
        continent = "South America"

    print(f"The randomly picked country is: {random_country}")
    time.sleep(1)
    ans = input("What continent is this country in? ")
    if ans.lower() == continent.lower():
        print(f"Correct! The country is in {continent}")
        points = points + 1
    else:
        print(f"Incorrect, it belongs to the continent: {continent}")
        if points == 1:
            print("You lost at, ", points, "point!")
        else:
            print("You lost at, ", points, " points!")
        break  
