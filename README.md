JMeter Setup and Execution
Follow these steps to execute your JMeter test plan:

Navigate to the JMeter Bin Directory:

Open your terminal and run:


cd /Users/saidinesh/Downloads/apache-jmeter-5.6.3/bin
Start JMeter (Optional GUI Mode):

If you need to launch JMeter in GUI mode, run:

sh jmeter.sh
Run JMeter in Non-GUI Mode:

To execute your test plan in non-GUI mode, use the following command:

jmeter -n -t /Users/saidinesh/Documents/JMeter/Flipkart.jmx -l /Users/saidinesh/Documents/JMeter/Results.jtl -e -o /Users/saidinesh/Documents/JMeter/
-n: Runs JMeter in non-GUI mode.

-t: Specifies the path to your test plan file (Flipkart.jmx).

-l: Specifies the log file for results.

-e: Tells JMeter to generate an HTML report at the end.

-o: Specifies the output folder for the HTML report.