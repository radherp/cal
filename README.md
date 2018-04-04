deriative(fx)
var('fx','x')
solve(diff(fx,x)<0,x)


concave up and down ,rel extrema
var('fx','x')
solve(diff(fx,x,2)<0,x)

local extrema ,inflection point
d=diff(fx,x)
solve(df==0,x) op=p
diff(fx,x,2).sybstitute(x=p)
\
solve(diff(fx,x,2)==0,x)
plot(diff(fx,x,2),x,-2,2,figsize=3)

solve(diff(fx,x,2)<0,x) rel extrema
solve(diff(fx,x,2)>0,x)

abs rel exteram ke liye limit for given point
############
newtons method
plot(fx,x,0,4,y=9,y=90)
n(x)=x-f(x)/diff(f(x))
x=float(25/10)
  for i in range(n):
     x=n(x)
     print(x)
#########
integral(fx,x,gien,given)

n,a,b,f is given
def l(f,a,b,n):
    d=(b-a)*1.0/n
    return d*sum([f(a+d*i)for i in range(n)])
 l(arg).n()
 def r(f,a,b,n):
    d=(b-a)*1.0/n
    return d*sum([f(a+d*(i+1)for i in range(n)])
 r(arg).n()
 
 def m(f,a,b,n):
   d=(b-a)*1.0/n
   xs=[a+d*i for i in range(n+1)]
   y=[f((xs[i]+xs[i+1])/2) for i in range(n)]
   return d*sum
  
 def t(f,a,b,n):
    d=(b-a)*1.0/n
    c=[2]*(n-1)
    c=[1]+coeffs+[1]
    v=[f(a+d*i)for i in range (n+1)]
    return (d/2)*sum([c[i]*v[i] for i in range(n+1)])
  t().n()
def s(f,a,b,n):
     d=(b-a)*1.0/n
     n2-int(n/2)
     co=[4,2]*n2
     co=[1]+co[:n+1]+[1]
     v=[f(a+d*i)for i in range(n+1)]
     return (d/3)*sum([co[i]*v[i] for i in range(n+1)])
  print s().n()
 ####
 partial
 var3x,y,z
 z1=f.diff(x)
 z2=f.diff(y)
 
##### 
 poly
x,y=PolynomialRing(QQ,2,"x,y").gens()
euler_method(fx,0,1,1/2,1)
 
 
 RR=RealField(sci_not=0,prec=9,rnd='RNDU')
x,y=PolynomialRing(RR,2,"x,y").gens()
euler_method(fx,0,1,1/2,1)
