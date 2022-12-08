# cosider-a-l1-vth-5-elements-print-the-values-at-the-index-position-2-3-6-handle-the-expection
def fileread():
    f=open("demo1.txt","r")
    c=0
    data=f.read()
    value=data.split()
    print(len(value))
    for i in value:
      if i=="programming":
        c=c+1
    print(c)
