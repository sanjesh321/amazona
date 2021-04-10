# Run Application by cloning repository from github `https://github.com/sanjesh321/amazona`

    Terminal Commands
        cd backend
        npm i
        cd .. && cd frontend
        npm i
        cd ..
        npm run dev

# Seeding Database

    @GET Request for seeding database 
        for seeding users - http://localhost:5000/api/users/seed
        for seeding products - http://localhost:5000/api/products/seed

# Login 
    Admin Login 
        email - sanjesh@gmail.com
        password - admin

        email - admin@gmail.com
        password - admin

    Customer Login
        email - customer@gmail.com
        password - customer


# Note 
    `npm run dev` starts react and nodejs server concurrently

# Run this application in debug mode on chrome/chromium browser

    1) open browser
        url: chrome://version
            copy `Executable Path`
    2) open vscode
        # debug mode
            create new launch.json
            change port
            add new configuration line and paster chrome executable path here
                "runtimeExecutable": "/chrome/executable-path"
    3) add breakpoints on desired lines
    4) run debugger

# Note 
    `launch.json` included in .vscode directory