# Matir

		build image
			cd ~
			git clone git@github.com:magimat/Matir.git
			cd Matir
			docker build -t magimat/matir .
                        docker push magimat/matir

		docker run --network host --name matir -d --restart unless-stopped magimat/matir
		
		
		
--network host pour que le discover fonctionne
