Test Spring Boot Jar post deployment : 
![image](https://user-images.githubusercontent.com/50335583/136151764-d3c5de8b-f228-4a57-9c92-e98941f3c2fc.png)

Confirmation of succesful execution of command logs:
![image](https://user-images.githubusercontent.com/50335583/136151714-ce5cfbff-d85e-4af7-b5ce-0d005a2707d0.png)

Command executed prior to ngrok :
./ngrok http 127.0.0.1:8080 -host-header="127.0.0.1:8080"

ngrok succeeded:
![image](https://user-images.githubusercontent.com/50335583/136178473-4f5e7a28-139d-4923-a425-04ceaff6e1b3.png)

Jenkins Declarative Build Succeeded with Polling with Post Deployment Step:
![image](https://user-images.githubusercontent.com/50335583/136183435-2811c34a-ac7b-484e-b3d6-d18a7dc30c07.png)

