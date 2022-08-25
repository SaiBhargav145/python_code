# python_codeNmae
#Name:P.Sai Bhargav
#mailid=sbhargav896@gmail.com
#collegeName=AVN institiute of engineering and technology
#passout=2022
#phone no:7981246429

class Planets:
    def __init__(self,Planet, Atmospheric_gasses,Moons,Rings):
        self.Planet=Planet
        self.Atmospheric_gasses=Atmospheric_gasses
        self.Moons=Moons
        self.Rings=Rings
    def Count(self):
        no_of_moons=0
        if self.Moons>0:
            no_of_moons+=Moons
        print(no_of_moons)    
    def no_gases(self):
        all_gases=""
        length=len(self.Atmospheric_gasses)
        if length>0:
            all_gases+=self.Atmospheric_gasses
        print(all_gases)    
def default_test():
    first_palnet= Planets(Planet="Mercury", Atmospheric_gasses="",Moons=0,Rings="NO" )
    print(first_palnet.Count())
    print(first_palnet.no_gases())
