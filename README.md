
1. git clone https://github.com/tubleronchik/Flask.git
2. cd Flask
3. docker build -t <name&tag_your_image> my_flask_app/ 
4. docker run -p 5000:5000 <name_of_your_image>


Delete:

1. docker ps -a
2. docker rm <ID_of_your_image>
