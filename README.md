
git clone https://github.com/tubleronchik/Flask.git
cd ~/Flask
docker build <name&tag_your_image> my_flask_app/ 
docker run -d 5000:5000 <name_of_your_image>


Delete:

docker ps -a
docker rm <ID_of_your_image>
