from kivy.app import App
 
class CalcApp(App):
    def touche(self, val):
        self.root.ids['monlabel'].text += val
    def erase(self):
        self.root.ids['monlabel'].text = ""
    def erase1(self):
        self.root.ids['monlabel'].text = self.root.ids['monlabel'].text[:-1]
    def calc_result(self):
        self.root.ids['monlabel'].text = str(eval(self.root.ids['monlabel'].text))
 
app = CalcApp()
app.run()
