# Race Registeration

This is the basic HTML page for Marathon Registeration.
Students new to Web development can try this. 

![image](https://user-images.githubusercontent.com/60788180/160063344-eada1590-c3c2-4bc7-9061-61ebf5daea88.png)

---
    <!DOCTYPE html>
    <html lang="en">

    <head>
       <meta charset="UTF-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Register Form</title>
     </head>

    <body>
    <h1>Race Registeration!</h1>
    <form action="">
        <div><label for="full name">Full Name</label>
            <input type="text" id="full name" required>
            <label for="last name">Last Name</label>
            <input type="text" id="last name" required>
        </div>

        <p>Select a Race:</p>
        <div><label for="id1">Fun Run 5k</label>
            <input type="radio" id="id1" name="race">
        </div>
        <div><label for="id2">Half Marathon</label>
            <input type="radio" id="id2" name="race">
        </div>
        <div><label for="id3">Full Marathon</label>
            <input type="radio" id="id3" name="race" checked>
        </div>


        <div><label for="email">Email</label>
            <input type="text" id="email" pattern="email" required>
            <label for="password">Password</label>
            <input type="password" id="password" pattern="password" required>
        </div>
      
        <div>
            <label for="select">Select age Group</label>
            <select name="" id="select">
                <option value="" checked>Under 18</option>
                <option value="">18-30</option>
                <option value="">30-50</option>
            </select>
        </div>
      
        <button>Register!</button>
      </form>
    </body>

    </html>

---
