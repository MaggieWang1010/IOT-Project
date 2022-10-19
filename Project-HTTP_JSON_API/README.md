## Step 1: Install Node.js on Ubuntu
## Step 2: Study Time Server and try to display current time in ISO format.
## Step 3: Study JSON
## Step 4: Study HTTP JSON API Server
## Step 5: Modify HTTP JSON API Server to support these requests from the client side
. Parse Current Time

http://localhost:8000/api/parse_currenttme
    
The browser displays current time in this way

{"year":2021,"month":09,"date":24,"hour":16,"minute":09}
    
Unix Time of Current Time

http://localhost:8000/api/unix_currenttme
    
The browser displays current time in a way similar to

{"unixtime":1376136615474}
