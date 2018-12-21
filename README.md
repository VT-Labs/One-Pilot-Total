# One-Pilot-Total
The Open-Pilot-Total is an automotive testing bench platform on automotive Firwall/IDS/IPS. It offers a bunch of practical toolkits and testing data repostiory for universities, reseach groups and secuity vendors.
Users can leaverage this platform to evaluate their POCs/pilot programs/demos/products.

# Testing datasets
format example:
{"timestamp":1500417011404,"seq":0,"id":0x78,"dlc":8,"data":[0x1,0x8,0x80,0x10,0x0,0x0,0x0,0x0]}

You have to convert your own CAN traffic files into this format before testing.

The low false positive and high detection rate are two critical factors for FW. The traffic files from two folders, "normal" and "attack", are used to test the false positive and detection rate. Attack traffic include various attck/hack scenarios, such as fuzzing, DoS, spoof, scan, etc.,

Users can use their own tools to generate more attacking traffic datasets. For example, if you have CAN Bus penetration testing tool or device, you can use the output traffic from that as the input feeds of the FW. Don't forget to convert the above format.
The datasets include both normal and attack CAN Bus traffic. 

# Tell us your research purpose
For the purpose of Good-faith research, the testing datasets is password-protected. Please contact us your affiliation, research purpose, how to use the datasets, etc., We need to make sure the datasets will be used for the sincerity of intention.
