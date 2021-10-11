# Titanic Passenger Data
Following is the list of passenger's name and their names boarded in the Titanic ship:

{% for entry in site.data.titanic %}

- {{entry.Name}}: {{entry.Age}} 

{% endfor %}
