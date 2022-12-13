import random

def sizegen(param1):
    if param1 == "small":
        return(random.randrange(10,100))
    elif param1 == "medium":
         return(random.randrange(101,500))
    elif param1 == "large":
        return( random.randrange(501, 1000))
    elif param1 == "huge":
        return( random.randrange(1001,2000))
    else:
        return("error")



def forest(sizeparam):
    forestsize = sizegen(sizeparam)


###land can be forest, plains, marsh, desert, tundra, mountains, lakes, or hills        

###each continent has a certain amount of its land taken up by one of the land types

def continent():
    
    continentsize = sizegen("huge")
    print("the continent is ", continentsize , " square miles")

    addterrain():

    ###loops through and adds small, medium, or large sections of terrain, until total combined size exceeds continentsize.
    ###when total combined size exceeds continentsize, a piece is removed until it no longer does. 



continent()
