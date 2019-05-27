## say hello
* greet
  - utter_greet

* out_of_scope
  - action_restart


## ask username 1
* greet
  - utter_greet
* password
  - utter_password
* inform
  - action_username
  - action_restart

## say goodbye
* goodbye
  - utter_goodbye


## ask for username 2
* inform
  - action_username
