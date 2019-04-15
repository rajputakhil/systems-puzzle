# Insight DevOps Engineering Systems Puzzle

## The systems puzzle challenge - 2019

### Following are the changes made to solve the puzzle:

1. Added "port=5001" after **app.run(host='0.0.0.0'** in line # 33 of the "app.py" file. The port value used is same as the one in the line # 12 of the "flaskapp.conf" file.

2. Changed the "nginx" port from "80:8080" to "8080:80" (line # 24) in "docker-compose.yml" file

