1:- Install JDK 8 or above 

2:- Install Maven by using below command:-
        $ wget https://mirrors.estointernet.in/apache/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.tar.gz
        $ tar -xvf apache-maven-3.6.3-bin.tar.gz
        $ mv apache-maven-3.6.3 /opt/

    # Maven Path Setup:-
            M2_HOME='/opt/apache-maven-3.6.3'
            PATH="$M2_HOME/bin:$PATH"
            export PATH

    # Verify Maven Installation with below command:- 
            $ mvn -version

3:- Install Vagrant with below command:-
        $ sudo apt-get install vagrant

        # Verify Vagrant Installation with below command:- 
                $ vagrant -v

4:- By a Cheap Domain From Godaddy or any other hosting websites.

5:- Create Account on GitHub

6:- Create Account on hub.docker.com

7:- Create Account on Sonarcloud==> "https://sonarcloud.io/login"

        # Create an Organization --> Click on Create Manually
            1:- Enter Project Name Unique (For e.g:- DevOps-project-0001)
            2:- Enter Key  (For e.g:- devops-project-0001)
            3:- Choose Plan for Free
            4:- Click on Create Organization