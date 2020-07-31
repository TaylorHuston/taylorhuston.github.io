#TaylorHuston.me

My portfolio and information website

Built with Jekyll<br />
Hosted on GitHub Pages

##Docker Instructions
###Official Jekyll Image

docker run -ti --name myBlog --volume=$(pwd):/srv/jekyll -p 4000:4000  jekyll/jekyll jekyll serve
docker start -i -a myBlog