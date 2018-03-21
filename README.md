# bucketlist

## prerequsites
* python (version 2 or 3)
* pip
* virtualenv
* sqlite

## installation

### OSX/Linux users:
1. clone or download and unzip this repo
2. cd into the new bucketlist directory
3. source nixSetup.sh
4. pip install -r requirements.txt
5. python ../manage.py db init
6. python ../manage.py db migrate
7. python ../manage.py db upgrade
8. ln bucketlist.db app/bucketlist.db
9. flask run

### Windows users using minTTY or other Cygwin shell:
1. clone or download and unzip this repo
2. cd into the new bucketlist directory
3. source setup.sh
4. pip install -r requirements.txt
5. python manage.py db init
6. python manage.py db migrate
7. python manage.py db upgrade
8. ln bucketlist.db app/bucketlist.db
9. flask run

### Windows users using command prompt:
1. clone or download and unzip this repo
2. cd into the new bucketlist directory
3. call setup.bat
4. pip install -r requirements.txt
5. python manage.py db init
6. python manage.py db migrate
7. python manage.py db upgrade
8. move bucketlist.db app/bucketlist.db
9. flask run
