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

<img src = "https://github.com/Nikita-Chorghe/Detection-and-Prevention-of-Various-Cyber-Attacks-on-Mobile-Network/blob/master/Images/Threat-Protect-Cyber-Security-Framework.png"  width = "300" height = "300"></img>
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

Mobile communications cannot be trusted completely. The basic ideology behind the cellular network is that, the mobile device sends an authentication request to the nearby mobile
towers providing the strongest signal for communication. IMSI stands for International Mobile
Subscriber Identity. The IMSI catcher device is one of the most effective threats capable of compromising the security of communication by compromising user privacy.Each sim has a unique
IMSI number comprising of Mobile Network Code (MNC), Mobile country code (MCC) and
Mobile subscriber identity (MSI).
Within a geographical area, multiple mobile towers are present. Since the mobile device
move within a geographical area, it keeps on reconnecting to a new mobile station which provides a better signal. An authentication protocol is followed before any mobile device is granted
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
An open cellular data set from OpenCelliD was used which contained all the necessary Information such as Location Id(LAC), Mobile Country Code(MCC), Mobile Network Code(MNC),
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

