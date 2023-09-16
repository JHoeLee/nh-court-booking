# North Hill Badminton Court Booking
Credits to Yong Jin

## Download the code (only do once)
Download zip file

## Installation & Setup (only do once)
#### Edit username and password
    cd nh-court-booking && pip install selenium
    echo username@student.main.ntu.edu.sg > login.txt & echo password >> login.txt

## Run the code from 11.50pm - 11.59pm (repeat whenever you need to book)
#### Disclaimer: the code will book the court 1 week from current date
    cd nh-court-booking
    python book.py --time 10 --court 6 
