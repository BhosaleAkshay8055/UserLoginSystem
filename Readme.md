# Activate virtual environment:
    Create new folder in root directory
    '''goto cd ./my_env/Scripts'''
    then ./activate

# then go back to root directory and install dependencies

2. pip install requirements.txt

3. Create .env file and your SECRET_KEY and DATABASE_URL like below 

    SECRET_KEY=secret_keyAkshay

    DATABASE_URL=postgresql://postgres:1234@localhost/userAuth

# then run code using the following command:

    '''uvicorn main:app --host 0.0.0.0 --port 8001 --reload'''

# after application start go to url: http://127.0.0.1:8001/docs

# and test the apis.

