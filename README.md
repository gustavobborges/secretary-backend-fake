# Secretary FAKE API

## Project description
<p>API Rest for appointments.</p>

## 🎲 Using API REST

### Appointment example:

<p>
    <b>name: </b>Consulta<br>
    <b>description: </b>Almoço<br>
    <b>place: </b>Centro<br>
    <b>date: </b>18/04/2021<br>
    <b>time: </b>12:30
</p>   

### 🎲 Requests HTTP:

<p>
    <b>GET</b><br>
    <b>- List all: </b>http://localhost:3004/appointments<br>
    <b>- List one: </b>http://localhost:3004/appointments/{id}<br>
</p>
<p>
    <b>POST</b><br>
    <b>- Create: </b>http://localhost:3004/appointments<br>
</p>
<p>
    <b>PUT</b><br>
    <b>- Edit: </b>http://localhost:3004/appointments/{id}<br>
</p>
<p>
    <b>DELETE</b><br>
    <b>- Delete: </b>http://localhost:3004/appointments/{id}<br>
</p>


## 🎲 Running backend (server)

### Prerequisites 

Before begin, you must have the fallowing items installed on your computer: 
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
In addition, it is good to have an editor to work with the code as [VSCode](https://code.visualstudio.com/)

```bash
# Clone this repositorie
$ git clone <https://github.com/gustavobborges/secretary-backend-fake>

# Access this directory
$ cd secretary-backend-fake

# Run the application
$ yarn start

```

### 🛠 Technologies

The following technologies were used in this project:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
