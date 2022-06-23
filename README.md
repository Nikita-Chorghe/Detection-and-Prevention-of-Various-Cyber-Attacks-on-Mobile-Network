# Detection and Prevention of Various Cyber Attacks on Mobile Network

## INTRODUCTION

With a global increase in dependence on digital devices, there has also been a global increase in incidents of cyber-attacks on these devices, and with respect to such incidents, India has been no exception. Hence, it is the need of the hour to have a system in place that will not only detect but also ward off such attacks.
Smartphones connected to a network are vulnerable to a number of security threats such as malware that can easily breach the defense systems of IOS and Androids. Hence, an in-build strong defense mechanism is crucial to protect security breaches and prevent data and monetary thefts. Solely solutions capable of analyzing behavior at every layer for indications of attacks can protect the devices effectively. Attacks exploit the overall national and business organizations through malware, viruses and worms, faux websites, unauthorized net access, and
different means of accessing private and organizational data.
In the present time, cyber-hacks are increasingly being launched for socio-political gains.
Mobile networks, spanning over a large geographical area, the user is able to communicate from
any location because of wide cellular coverage. Determining location details of users requires
the use of software and also a prompt response as it changes rapidly. Mobile operators providing information services to users are vulnerable to nameless attackers who intend to abuse the
provider and their network. Common threats namely hacking of web sites, copyright infringement, and illegal communications exist. Mobile operators don’t have any predefined guidelines
to deal with such threats. Relatively simple solutions have been provided by Internet service
providers (ISP’s) which can be incorporated in the mobile environment. New threats exploiting
mobile network continue to appear. Detection of cyber-attacks help organizations in protecting
devices, apps and data from malicious attacks.
The results of data thefts from smartphones can be devastating and far-reaching. It can affect
people not only at personal level but also society at large.

## Objective

Every business organization or individual user is a part of the network. These organizations
and individuals are constantly endangered by cyber attacks. Cyber risks pose horrifying threats
to them with increasing financial frauds and Cyber terrorist act. Governments, multi-national
corporations, people face persistent threats, experience frauds, extortion and defacing of vital
IT infrastructure. With increasing use of smartphones, threats have also increased. Business
organizations and individuals face huge losses due to hacking or malicious attack. Thus it
becomes necessary to detect and prevent these attacks to make the mobile connection secure. It
is a necessity to provide a secure environment to mobile users.

## Problem Statement

Any attack launched on a any computer or mobile network with the intention of gaining
unauthorized access for ulterior motives like stealing data or money, stalking, breaching privacy
etc. can be labelled as a cyber-attack. Such attacks can be launched using viruses, worms,
backdoor traps, malwares, etc. Such attacks can threaten and cause serious damage to everyone
at personal, corporate, social, political, or national levels. Hackers can steal vital data and sell
it to rivals on dark web.
Mobile devices being portable, multi-functional etc, the number of cell phone users are
ever increasing. Thus there is a great need of mobile security. Taking into consideration these
points, a system will be developed to make it easier for the users to detect different threats and
efficiently avoid those risks.

<img src = "https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/Threat-Protect-Cyber-Security-Framework.png"  width = "400" height = "400"></img>
 NIST Framework Architecture
 
 1. Identify:  Our system should identify the type of attack and what harm it will cause to our
system. Identify is first function of the framework. It helps organizations to develop
a better understanding on how to manage risks associated with the cyber threats.

 2. Protect:  The protect functions helps to reduce the impact of the cyber attack by incorporating
the best security practices for data protection and overall system protection.
 3. Detect: The Detect Function attempts to identify the presence of a cyber attack. It performs detection at regular intervals. It pre-defines a set of protocols to be followed in order to detect the presence of
attack.
 4. Respond:  The respond function is a series of actions to performed after successful detection
of a cyber attack in an attempt to successfully mitigate the attack.
 5. Recover: t is set of steps to be followed in order restore any and all activities, services and
capabilities damaged or affected by the attack.

## IMSI Attack

Mobile communications cannot be trusted completely. The basic ideology behind the cellular network is that, the mobile device sends an authentication request to the nearby mobile
towers providing the strongest signal for communication. IMSI stands for International Mobile
Subscriber Identity. The IMSI catcher device is one of the most effective threats capable of compromising the security of communication by compromising user privacy.Each sim has a unique
IMSI number comprising of Mobile Network Code (MNC), Mobile country code (MCC) and
Mobile subscriber identity (MSI).
Within a geographical area, multiple mobile towers are present. Since the mobile device
move within a geographical area, it keeps on reconnecting to a new mobile station which provides a better signal. An authentication protocol is followed before any mobile device is granted
access to connect to a mobile tower. The device sends its IMSI number to the base station for
authentication. After executing security algorithms and authenticating the device, it is granted
connection to the base station.

<img src = "https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/imsi.png"  width = "300" height = "300"></img>

The attacker acts as fake base station for the mobile device. This results in the device sending
its IMSI number to the attacker instead of base station. The attacker captures the IMSI number.
Now the attacker acts as a fake mobile device and authenticates itself using the captured IMSI
number. Once authenticated attacker performs man in the middle attack and captures each and
every data packet thus proving to be a threat to user privacy. The attacker can eavesdrop on
calls and record them, sniff SMS messages to redirect them, track location of the user, retrieve
data from the target phone such as pictures, document etc. The proposed framework captures
the current location using Loaction Id(LAC) provided by OpenCellId. It stores a database of
all the present cell towers in that location. During it authentication, it checks whether the same
cell towers are present or not. Based on the detected information, it further authenticates or
terminates the connection request.

<img src = "https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/IMSIflowchart.jpg"></img>

Each mobile device needs to connect to a base station in order provide cellular network to
the user. Therefore the proposed algorithm as shown in Figure 3.3 performs a series of steps
before the connection is granted in order to eliminate the threat of IMSI attack.
An open cellular data set from OpenCelliD was used which contained all the necessary Information such as Location Id(LAC), Mobile Country Code(MCC), Mobile Network Code(MNC),
Cell-Tower Id(CID), type of network etc. Based on this data set a new data set was derived
consisting of the LAC and sum of CID for that particular LAC. Each time a device request a
connection to a base station:

• The current location of the device is captured.
• The sum of CID for that LAC is calculated.
• The value is matched with sum stored in the database.

Only if the values match, GSM algorithms(A3,A5,A8) algorithms are performed for further
authentication and privacy. If the values do not match, the request to connect to a new base
station is terminated based on the possibility of an attacker trying to perform IMSI attack.

## Identity Theft Attack

Identity theft is a misdeed in which masquerader steals the information from a legitimate user
and use that information to impersonate someone. Your passwords are stored in system using
special algorithms known as hashing , Hackers try to access that file from system. Most of the
time password is kept for important files. Leading to the immediate impact of certain significant
losses such as cash and debt securities, individual victims of identity theft can have significant
intangible costs, including damaging their reputation and credit report, which could prevent
them from getting a loan or even getting a job. Depending on the circumstances, identity theft
can take years to recover.
The businesses of their employees have become an enemy to steal their identity and face significant costs associated with credibility and trust. Once the business’s reputation has been damaged, it is necessary for that business to be able to use it through additional security measures
to assure customers that it will not do so again. It’s necessary to know whether the password
has been hacked or not.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/idtheft.jpg"></img>

A cyber-attack is a deliberate attempt to exploit hardware/software vulnerabilities and to
capture, store, alter, misuse private data for personal gains. It is done with the help malicious
scripts, alter the software code or introduce backdoor traps, worms, viruses in system and retrieve sensitive information which may lead to identity theft. Users also use mobile as a means
of online transaction, storing financial information and passwords which makes it important to
secure the network over which communication is done.
System can be used to detect such attacks and thus mitigate such threats and secure user
data.We have developed a hacked password checker(an example shown in Fig 3.6), which will
work as an alert system for users. It will check whether the password has been hacked or not. It examines the password and if that password matches the list of passwords that have leaked then
we will report to the user.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/theft.jpg"></img>

 The database of the leaked
passwords is created. The user enters his/her password. The system will check if that password
matches the user entered password if that password matches then the user will be notified or
else the user’s password is not leaked.

Procedure : We have developed a hacked password checker, which will work as an alert
system for users. It will check whether the passwords have been hacked or not. It examines the
password and if that password matches the list of passwords that have been leaked, it will report
to the user.
1. A leak data set is being created. A new associated set of data is created when each leaked
password is converted to hash value.That hash value is stored.
2. The system takes an input from the user. The user enters his/her password. User entered
password is converted into hash value.
3. If that hash value matches with any one of the values from the file, that password is leaked.
The system will notify the user that his/her password has been previously hacked.
4. If the hash value does not match then the user-entered password is not leaked and can be
safely used.

## Smishing Attack

Phishing was introduced from the word fishing which indicates the activity of catching fish
using a bait. The word fishing is combined with the term phreak, which refers to hacking of
computer systems to obtain free calls, and transformed into phishing to simply indicate hacking
by phishing.
Phishing is a type of cyber-attack whose objective is to steal people’s confidential information using a bait. The term smishing is, on the other hand, is obtained by combining the two
words, SMS and Phishing and was used by David Rayhawk of McAfee for the first time on
August 25, 2006. Attackers intend to steal the personal information of the victims using the
content they send in SMS messages rather than other media.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/smishingmain.png"></img>

Some of the techniques used by researchers to prevent smishing are briefly discussed below.

1. Content-Based Filtering:
• The content present in the message is assessed for suspected URLs, E-Mail IDs,
Phone Numbers and Keywords using this technique. Smishing content filtering involves examining the text present in the SMS.
• The smishing message is categorized based on the contents which are present in the
text.
• Sometimes content-based filtering is performed based on some set of rules which is
also called as rule-based classification.

2. Blacklisting:
• In this approach, a list of suspicious IP addresses and URLs are maintained by
trusted sources which are then used to identify fraud websites.
• This approach is used by various browsers that communicate with trusted servers to
obtain a list of blacklisted URLs.
• As blacklisting cannot detect zero-day phishing attacks,blacklists need to be frequently updated.
• The approach works well as long as the list is regularly updated and this method
yields low false-positive results.

• The approach works well as long as the list is regularly updated and this method
yields low false-positive results.
3. Whitelisting:
• In this approach, a list of authorized URLs are stored which is named as whitelist
and this can be used for identification of genuine websites. As,checking genuine
websites for malicious features is avoided by using this method,it reduces the complexity of the classification method.
• Whitelisting alone cannot be used for smishing detection because it does not identify
the malicious features of the URLs.

4. Heuristic methods:
• Some researchers have used a heuristic-based approach in which features are discriminated from both the legitimate SMS and smishing.
• SMS are extracted and a training dataset is build based on the extraction. The
most malicious features identified based on the classification will be finally used
for smishing message classification.
• When the users receive a new SMS, then the machine learning algorithm predicts
the message based on the learning from the training dataset.
• This method gives high accuracy but if the maliciousness check is not conducted on
the URLs then can it lead to false-positive results.

5. URL Based methods:
• In this approach, the URL present in the text message is further analyzed to inspect
the behavior of the URL.
• The malicious behavior of the URL is inspected and the messages containing malicious URL is categorized as smishing message


• Random forest algorithm :
Random forest is a supervised learning algorithm which is used for both classification as
well as regression. But most of the times, it is used for classification problems. As we
know that a forest is made up of trees and more trees means more dense forest. Similarly,
random forest algorithm creates decision trees on data samples and then collects the prediction from each of them and finally selects the best solution by means of voting. It is
a grouped method which is better than a single decision tree because it reduces the overfitting by averaging the result.The random forest is quick to train and highly accurate.

• Feature Extraction:
Feature extraction is the process of transforming original data to a data set where the number of variables is reduced, which contains the most discriminatory information. This will
reduce the data dimensionality, remove redundant or irrelevant information, and transform it to a form more appropriate for classification.

• The Machine Learning Modeling process:
The process of modeling means training a machine learning algorithm to predict the labels
from the features, tuning it for the business need, and validating it on holdout data.The
output from modeling is a trained model that can be used for inference, making predictions on new data points

## Results
The figures below explain the flow of Imsi attack detection and GSM security
authentication before the device establishes a connection with the cell tower.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/imsi1.jpg"></img>

Displays the various details such as IMEI, IMSI number etc. of a cell
phone connected to a network.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/imsi2.jpg"></img>

Displays the details of the current cell tower to which the phone is
currently connected.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/imsi3.jpg"></img>

Depicts the scenario where in an intruder is detected as the sum of
cell-id’s do not match.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/db1.jpg"></img>

 Depicts the scenario wherein the sum of cell-id’s match.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/db2.jpg"></img>

After the cell-id’s match, GSM authentication is carried out. Fig 6.5 shows
the A3 authentication process where SRES and RES are matched for further
authentication.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/A3algo.jpg"></img>

Once A3 authentication is successful, 64 bit cipher key is generated for encryption/decryption purpose using A8 algorithm as shown in Fig

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/A8algo.jpg"></img>

Once A3 authentication is successful, 64 bit cipher key is generated for encryption/decryption purpose using A8 algorithm

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/A5algo1.jpg"></img>

Displays the encrypted result of user text based on A5 algorithm.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/A5algo2.jpg"></img>

 Displays the decrypted result of cipher text based on A5 algorithm.
 
<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/A5algo2.jpg"></img>
 There are two possible scenarios:
• User password is leaked
• User password is not leaked

Nowadays,most of the users are conducting banking transactions through smart
phones, many SMiShing messages claim to be coming from a financial institution. Whenever the messaged is received from their bank,many of the users
tend to not think twice before acting. Attackers always use legalized sounding
language and even some branding to assist their pretext.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/inputmsg2.png"></img>

Nowadays,most of the users are conducting banking transactions through smart
phones, many SMiShing messages claim to be coming from a financial institution. Whenever the messaged is received from their bank,many of the users
tend to not think twice before acting. Attackers always use legalized sounding
language and even some branding to assist their pretext.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/inputmsg1.png"></img>

shows another example of a Smishing attack.

<img src="https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/inputmsg3.png"></img>

URLs of websites are separated into 3 classes as shown in Fig:
• Benign(SAFE): Safe websites with normal services
• Spam(SUSPICIOUS): Some of the webistes attempt to flood the user with
advertising or sites such as fake surveys and online dating etc.
• Malware(UNSAFE): Website created by attackers to install malwares,viruses
on your system,gather sensitive information, or gain access to private computer systems.

