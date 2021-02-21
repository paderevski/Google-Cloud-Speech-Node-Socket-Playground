this works. sends local mic data to google for transcription
something with environment is off though so you need
export GOOGLE_APPLICATION_CREDENTIALS=./key.json 
where key.json is the local file here that stores my private credentials.
this should be read in from .env but doesn't seem to be

