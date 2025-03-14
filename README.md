# ADA502_Fireguard_Group_4

# Project Structure
![image](https://github.com/user-attachments/assets/42c0afe2-7434-40c5-97c0-7dc7eaeeb512)<br>
This project is comprised of 4 primary microservices, 
# An api project
This project runs pythons Fast Api to serve api requests
# An auth project
# A business logic project
# A Database project

The basic structure for the DB, will probably be extended in the future <br>
<img width="772" alt="image" src="https://github.com/user-attachments/assets/9e81b259-ca86-4a1d-853f-7f85bde95520" /><br>

Flow for creating a userevent
![image](https://github.com/user-attachments/assets/b508cd73-a565-4a31-b54d-7b6d8ba8005e) <br>

Flow for sending events on datapoll
![image](https://github.com/user-attachments/assets/bd051f39-c079-48da-a6de-ddca196d8f7a) <br>





# Quick start

To get started <br>

Run the docker compose for the database <br>
Run each of the dotnet projects with https <br>

The database project seeds the database with some mockdata <br>

To test go to https://localhost:7028/api/firerisk/{id} (the seeder seeds 4 values so 1-4 should give data back) <br>
