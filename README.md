# Git-Exercise1

class analogMemir:
    def init(self,volt):
        self.volt=volt
    def ToDigital(self):
        int=int(0*204.6)
        binary= format(int,'b')
        return binary
    def SetDigitalValue(self):
        digValue = self.ToDigital(self)
        self.digValue = digValue
