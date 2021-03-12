# rasa_bot
#Execute below command first.

rasa train

# Execute below command and rasa server will be starting up based on models built by first command.
rasa run -m models --enable-api --cors "*" --debug