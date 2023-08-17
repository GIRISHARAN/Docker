# Pusuluru Giri Sharan Reddy
# Master of Applied Computer Science, Dalhousie University, Canada


For Docker:
    (Note: Ensure docker desktop is present in your system)
    1) Download docker-compose and file.dat files to an empty folder
    2) open any command terminal type command "docker-compose up" command and press enter
    3) once the command is run successfully, open postman application and test by sending a HTTP POST request to http://localhost:6000/calculate with bosy in JSON as given below
        {
           "file":"file.dat",
           "product":"<product-name>"
        }
	4) If product with the given name is available in the file.dat it will give total cost of 		the products else zero
	5) Once you are done with testing, you can type "docker-compose down" command in other terminal to stop and remove the containers that were created.