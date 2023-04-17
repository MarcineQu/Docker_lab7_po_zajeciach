# Docker_lab7_po_zajeciach

**Plik Dockerfile**

![image](https://user-images.githubusercontent.com/83167368/232523224-9d2b7fd5-ffba-44eb-9f2b-6a4f28eb868b.png)

**Polecenia użyte:**

docker buildx build -t docker.io/marcinequ/lab:zadanie_zaj --platform linux/amd64,linux/arm64 --push .
![image](https://user-images.githubusercontent.com/83167368/232521778-09ecd63c-c380-4fa9-a518-b26bc332c9a3.png)

docker run -d -p 8080:80 marcinequ/lab:zadanie_zaj
![image](https://user-images.githubusercontent.com/83167368/232521947-c6a852c5-b7f2-4bf6-9ef0-1a1fc3e1eadb.png)

docker buildx imagetools inspect marcinequ/lab:zadanie_zaj
![image](https://user-images.githubusercontent.com/83167368/232522251-80e61473-0e83-4c14-86f0-a25801abe42d.png)

**Wyświetlanie imienia i nazwiska na stronie**

![image](https://user-images.githubusercontent.com/83167368/232523328-8b26afb1-f68a-4893-835b-7e81411f8a45.png)
