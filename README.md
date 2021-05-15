from tkinter import *


class Player:

    def __init__(self):
        self.jajaja = Tk()
        self.jajaja.title("Connection")
        self.jajaja.geometry("1080x1980")
        self.jajaja.minsize(480, 360)
        self.jajaja.iconbitmap("ico.ico")
        self.jajaja.config(background='#FEFDFD')
        self.frame = Frame(self.jajaja, bg='#FEFDFD')
        self.create_widgets()
        self.frame.pack(expand=YES)

    def create_widgets(self):
        self.create_title()
        self.create_subtitle()
        self.bouton()

    def create_title(self):
        label_title = Label(self.frame, text="Salut, tu peux ecrire ton nom ici", font=("Arial", 40), bg='#FEFDFD',
                            fg='black')
        label_title.pack()

    def create_subtitle(self):
        label_subtitle = Entry(self.frame, font=("Courrier", 25), bg='#FEFDFD',
                               fg='black')
        label_subtitle.pack()


    def bouton(self):
        bonto = Button(self.frame, text="Connection", font=("Arial", 25), bg='#E1EA1C', fg='black', command=self.boto)

        bonto.pack()

    def boto(self):
        self.jajaja.quit()
        hh.fefe.mainloop()




class cookie:

    def __init__(self):
        self.fefe = Tk()
        self.fefe.title("My Application")
        self.fefe.geometry("1080x1980")
        self.fefe.minsize(480, 360)
        self.fefe.iconbitmap(None)
        self.fefe.config(background='#41B77F')
        self.frame = Frame(self.fefe, bg='#41B77F')
        self.createee()
        self.frame.pack(expand=YES)

    def createee(self):
        self.coo()
        self.counter()
        self.boutique()

    def coo(self):
        bouton_coo = Button(self.framee, image=("Py"), command=self.countere())
        bouton_coo.pack()

    def countere(self):
        compt += 1
        self.compt.pack()

    def counter(self):
        countery = Label(self.framee, text=("Tu as {} Cookie"), textevariable=str(self.countere),  bg='#FEFDFD',
                         font=(("Arial"), 25), fg='black')
        countery.pack()

    def boutique(self):
        pass


app = Player()
app.jajaja.mainloop()
hh =  cookie

# j ai un prolème avec ma deuxieme fenetre
