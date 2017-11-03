### Deployment guide

# Ovo ti je veliki heade

## ovo ti je manje header

### ovo ti je jos manji

## Slijedce je lista
- elemtn1
- elemtn 2
- element 32
- sdkasdasdasd
- asda
- sda

## OVako dodajes code - sa tabom i onda mozes opisati sta radi
	echo "\nStarting Tests!!\n"
	# Running the Jmeter Scripts
	for x in $scriptlocation/*.jmx; do
	  echo "Running the Script $x"
	  sh $JMETER_HOME/bin/jmeter.sh -n -t $x -l $reporttarget/jtl/test.jtl
	done
	echo "Test Runs are Over!!"


Ovo su sad izmjene neke nove koje pravimo ovdje


### Steps