# week-1
p= int(input("enter principale"))
r=int(input("enter rate"))
t=int(input("enter time"))
amount=p*(1+r/100)**t
ci=amount-principale
print(round(ci,2))
