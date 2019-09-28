# Python-Flappy-Bird-AI
Flappy bird with python and AI

NEAT-python algoritmo:  
	Usa:  
		**INPUTS** <- Necesitamos dar datos, posicion de Bird (y), distancia entre el Bird y las tuberias (TopPipe, BotPipe)   
		**OUTPUTS** <- Salta o no salta.  
		**Activation Functions** <- Tan(H) checkearemos si el numero es -1 o 1 lo que determinara si salta o no salta   
		**Population Size** <- 100 birds Gen 0 testear elegir loe mejores mutarlos y GEN1 100 birds   
		**Fitness Function** <- Como los pajaros se van a volver mejores tener presente en como los puntuamos y elegimos los mejores, se hara por   distancia por cada posicion que avance  
		**Max Generations** <- 30 generaciones.   
