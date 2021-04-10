# how to run application and cloning repoisitory from github

    Terminal Commands
        cd backend
        npm i
        cd .. && cd frontend
        npm i
        cd ..
        npm run dev

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
                "runtimeExecutable": "/chrome/path"
    3) add breakpoints on desired lines
    4) run debugger

# Note 
    `launch.json` included in .vscode directory