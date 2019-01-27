# Matir

		build image
			cd ~
			git clone git@github.com:magimat/Matir.git
			cd Matir
			docker build -t magimat/matir .
                        docker push magimat/matir

		docker run --network host --name matir -d --restart unless-stopped magimat/matir
		
		
		
--network host pour que le discover fonctionne


## broadlink python library

librairie utilisée pour enregistrer les codes:

https://alexbelle.wordpress.com/2017/05/24/how-to-control-ibroadlink-rm-mini-3-from-raspberry-pi-or-ubuntu-16-04-lts/

https://github.com/mjg59/python-broadlink
