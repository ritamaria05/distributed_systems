# compile with

$ javac -cp ../Poisson/src/ UsePoisson.java

# to run the program you must provide the classpath with the current
# directory to find UsePoisson and also the path to the "poisson" package

$ java -cp .:../Poisson/src UsePoisson 10

# this gets you a sequence of events with an average of 10 per minute

