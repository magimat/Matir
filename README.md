# Matir

		build image
			cd ~
			git clone git@github.com:magimat/Matir.git
			cd Matir
			docker build -t magimat/matir .
      docker push magimat/matir

		docker run -p 4000:80 --name matir -d --restart unless-stopped magimat/matir
