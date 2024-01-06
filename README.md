# HAZESOFT-T1
## How to Run

Follow these steps to set up and run the project locally:
    (note you need to setup docker beforehand to create docker image and to run docker container)
1. **Clone the Repository:**

       git clone https://github.com/Sulav-Adhikari/HAZESOFT-T1.git

2. **Navigate to the Project Directory:**
       
      Open a command line interface and navigate to the location where the `HAZESOFT-T1`directory is located. Use the following command:

      cd path/to/HAZESOFT-T1

3. **Build the Docker Image:**

      docker build -t your-image-name

4. **Run the docker container:**

     docker run -it -p 9000:80 --name your-container-name your-image-name

5. **Open your browser:**

     Go to http://localhost:9000/site/index.html
    

     
     

