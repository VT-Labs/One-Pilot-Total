# One-Pilot-Total
The Open-Pilot-Total is an automotive testing bench platform on automotive Firwall/IDS/IPS. It offers a bunch of practical toolkits and testing data repostiory for universities, reseach groups and secuity vendors.
Users can leaverage this platform to evaluate their POCs/pilot programs/demos/products.

# PLEASE READ CAREFULLY BEFORE USING THE DATA.
THE DATA IS PROVIDED “AS IS” AND “AS AVAILABLE”.  WE SHALL NOT BE LIABLE FOR DIRECT, INDIRECT, INCIDENTAL, PUNITIVE, EXEMPLARY, SPECIAL OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS AND PROPERTY DAMAGE, EVEN IF WE WERE ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  IN NO EVENT SHALL OUR TOTAL LIABILITY TO YOU FOR ALL DAMAGES, LOSSES AND CAUSES OF ACTION.

# Tell us your research purpose
For the purpose of Good-faith research, the testing datasets is password-protected. Please contact us your affiliation, research purpose, how to use the datasets, etc., We need to make sure the datasets will be used for the sincerity of intention.

Please contact us at info(at)visualthreat.com for dataset password.

# Data use agreement
The Open-Pilot-Total data may include software, binary data, testing datasets, scripts, videos, other contents (“Data“). You may not decompile, reverse engineer or disassemble the Data. You agree that you will not tamper with, impair or damage any One-Pilot-Total realted websites.

To access and download the Data, you must contact us and to become a registered user of One-Pilot-Total by providing contact information.  No purchase or payment is required for you to be a registered user. We may suspend or terminate your account and your ability to use the Data if you engage in, encourage or advocate for copyright infringement or any illegal conduct. You are responsible for keeping your username and password confidential, and you are responsible for all activities and use of the Data under your account. You agree to promptly notify us of any unauthorized use of your username, password or other account information.

The Data may be available only for limited periods of time and may be removed, replaced, changed or updated at any time at our sole discretion and with or without notice to you.

# User Feedback
You may submit your automotive Firewall/IDS/IPS testing resutlts to us to make the One-Pilot-Total better. You acknowledge that One-Pilot-Total shall have the right (but not the obligation) to use the testing results in the feedback to the public.

# Testing datasets
format example:
{"timestamp":1500417011404,"seq":0,"id":0x78,"dlc":8,"data":[0x1,0x8,0x80,0x10,0x0,0x0,0x0,0x0]}

You have to convert your own CAN traffic files into this format before testing.

The low false positive and high detection rate are two critical factors for FW. The traffic files from two folders, "normal" and "attack", are used to test the false positive and detection rate. Attack traffic include various attck/hack scenarios, such as fuzzing, DoS, spoof, scan, etc.,

Users can use their own tools to generate more attacking traffic datasets. For example, if you have CAN Bus penetration testing tool or device, you can use the output traffic from that as the input feeds of the FW. Don't forget to convert the above format.
The datasets include both normal and attack CAN Bus traffic. 

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

