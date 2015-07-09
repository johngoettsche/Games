game : districts.u organizations.u game.u
	unicon -o game districts.u organizations.u game.u
	clean
	
game.u :	game.icn districts.u
	unicon -c game.icn

organizations.u : organizations.icn districts.u
	unicon -c organizations.icn

districts.u : districts.icn
	unicon -c districts.icn
	
DAO.u : DAO.icn
	unicon -c DAO.icn
	
clean : *.u
	rm *.u
	