# En français correct s'il vous plaît!
definition du titre du correcteur d'orthographe.

--- il faut importer un dictionnaire en lecture seule ---( myspell peut etre)

def dictionnaire ()-> list:
   dictionnaire = []
   hunspell = open("classique-fr",'r')
   hunspell.split("/","0","1","2","3","4","5","6","7","8","9")
   "classique-fr".close 
   return lexique
   
   
def texte (str)-> list:
   texte = open("texte à corriger","r")
  paragraphe = [].append(texte)
  texte.close
  return paragraphe
  
def extraction_données (list)-> list:
  mots = [] 
  liste_mot = texte.split(" ",";",",",".","!","?",'"',":"," ")
  mots.append(liste_mot)
  return mots
  
def recherche (mots:list)-> str:
  mal_orthographié=[]
  for m in range (len(mots)):
    mal_orthographié. append [m]
  return mal_orthographié
  
def main():
  erreurs = recherche
  texte = "texte à corriger"
  texte = str(input("Entrer le texte à corriger:{}".format(paragraphe)))
  erreurs.append (mal_orthographié)
  resultat = "les mots mal orthographiés sont{}.format(recherche)"



main()
