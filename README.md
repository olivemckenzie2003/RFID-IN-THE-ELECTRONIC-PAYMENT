Study Completed 2006

# RFID-IN-THE-ELECTRONIC-PAYMENT
RFID IN THE ELECTRONIC PAYMENT: TO INVESTIGATE  THE POSSIBILITY OF RFID AND BIOMETRICS BASED AUTHENTICATION MECHANISM FOR  ENSURING SECURE ELECTRONIC PAYMENT

Chapter 1. INTRODUCTION

Since passwords are easily forgotten, lost, and discovered using password cracking software, they have now begun to be seen as an insecure method of personal authentication and a weakness in the security of many computer systems. Therefore, more and more organisations and individuals are considering RFID and biometric as the technology that will increase security.
0.1	Problem Statement
RFID Radio Frequency Identification is made up of an antenna, a transceiver, and a transponder. The antenna transmits a signal using radio frequency waves to activate the transponder.  The transponder then transmits data back to the antenna. This data tells the programmable logic controller that some kind of action needs to take place, such as raising an access gate, or to access a database to perform a monetary transaction. The transponder is known as the tag and most of them are not battery powered but are powered with the initial radio signal to transmit their response. RFID tags are microchips that are very small. For example, 0.3 millimetres square in size (RFID Journal, 2003), and continuously listens for a radio query. When it responds it transmits its unique ID code. RFID does not need a straight-line-of-sight or direct contact for scanning purposes. (Webopedia, 2005) The RFID signal can be short range or long range. RFID is used widely for the stock control, tracking of goods in the retail sector, and implanted in livestock and domestic pets.

Biometrics uses equipment and software to recognise human features such as face, fingerprints, hand geometry, handwriting, iris, retinal, vein, voice and personal behaviour that is said to uniquely identify an individual. 

For biometric data to be use has an effective form of authentication, there are certain properties that the information gathered from biometrics should consist of which are; measurable in a short period of time, remain unchanged for a long period of time (Invariance), unique from one individual to another, the information capturing technique must be acceptable to the majority of the public, the data captured must be able to be stored in a small amount of space, so that it is easy to manipulate, the data capturing process and the data itself must be reliable and reproducible, the privacy of an individual must be maintained. (Brüderlin 2001)

0.2	Description of Problem 
The problem to be solved is to prove that it is possible to use biometrics and RFID as a method of personal authentication during the process of an electronic payment.

A user of the Biometric and RFID authentication technologies should be provided the technology in an easily portable form such as a card. This card should allow them to make payments in shops, over the Internet and whilst using the telephone.

The reason for considering biometrics and RFID as a method for personal authentication is because of the increase in the impersonation of individuals through; credit card thefts, personal information thrown out in domestic household garbage, access to computer data and access to restricted areas.  
0.3	Approach to the Problem

The approach to solving this problem was to attach to the computer a Feig ID-ISC.PR100 Short-range RFID reader 13,56 MHz, which reads RFID, tags for personal Identification. This RFID scanner would communicate with the Sun Java System RFID Software 2.0. A biometric BioStik scanner was also attached to the computer to read fingerprints for the purpose of personal identification.

The two technologies were available to the user through GUIs. The GUIs were custom built using Java code. After the user was biometrically and RFID verified, the user was allowed to use the system to make an electronic payment.

Chapter 2. Background and review of literature

This chapter introduces the feasibility of biometric and RFID technology to be used for the personal authentication of an individual for the purpose of making an electronic payment. The advantages and disadvantages of such technology must be considered, and the alternative implementations possible. 



Biometric recognition is a very effective means of authentication, however from research it has been shown that the scanning of the iris is the most effective method. It has been said that there is a one in six million chance of an error occurring and for a fingerprint there is a one in a million chance of an error occurring (René Brüderlin, 2001). However less people tend to loose their fingers and eyes and other body parts in comparison with the loss of credit cards, direct debit cards and the non-recollection of passwords. (Romsey Associates, 2001).

The value of the information in the above table (Table 1) is affected greatly by the fault tolerance level set on the biometric software and devices. If the fault tolerance is low the system will be more secure, however user friendliness will decrease. (Body Check: Biometrics Defeated).


![image](https://github.com/olivemckenzie2003/RFID-IN-THE-ELECTRONIC-PAYMENT/assets/115945473/0d2593ff-85ef-47e9-8008-51be43ec818c)



In normal circumstances biometric features cannot be shared. Biometrics systems reduce maintenance in comparison with a password system, and a biometric system allows for faster login, no password to be remembered and increase security. (International Biometric Group 2002)

Biometric systems have special techniques that can be implemented to reduce the risk of overcoming verification through fraudulent methods. For example, the finger scanner recognises the unique conductive nature of the finger; blood flow, ridges at the periphery of the print so that they are as it should be in a live finger when placed on the scanner. The voice scanner can generate a random sequence of numbers for each scan thus making it difficult to utilise a pre-recorded voiceprint. Facial scan requires the user to blink, smile and so on for the template to be accepted. The iris scan measures the dilution of the iris under various measures of light shining on the eye.  The retina scan would fail to verify a dead eye because the vein structure of the retina changes just a few minutes after death. At present it appears that there are no special detection measures developed for the live hand, therefore a dead hand could verify a hand-scan. (International Biometric Group 2002)

With all these special techniques in place it is still possible to defeat any biometric system with enough time, money, and attempts, and without special security techniques put into place it may be easier to defeat the biometric system than the existing non biometric systems. (International Biometric Group 2002)

It is argued that biometric data does not perfectly uniquely identify an individual at all times in the sense that false matches occur due to the variance of template quality. Sometimes two templates produce a false non-match. (International Biometric Group 2002)

Biometric data cannot be forgotten, however it can be borrowed and stolen. It is possible to lift a person’s fingerprint off a door handle or a drinking glass. If a database holding a fingerprint is accessed, then it can be stolen and borrowed. However, if the biometric data is encrypted the criminal will need the key to decrypt it or use brute force decryption technique.

Fingerprint verification is a good biometric choice because it is easily accepted as non-intrusive and best suitable in a controlled environment where users can be trained how to use the fingerprint reader. The reader should be able to differentiate between a live finger and a finger that has been dislocated from an individual, or a finger that is attached to a dead body.

Biometric enrolment must be carried out correctly because this can lead to high false rejection rate during verifications. A biometric system has no proof that the person proving biometric data is who they claim to be.

The user has to remember for the facial-scan, the facial expression and for voice recognition device the voice used for enrolment on the system. If the biometric verification fails due to a change in body feature, the biometric template must be updated, or the system needs to have a secondary measure of verification such as the use of a password. If possible, a biometric system should hold more than one method of biometric verification because there is always a percentage of the population that is unable to supply specific biometric data.

The biometric voice-scanner may have difficulty to verify a voice, in a noisy environment, or if user has a cold or speaks quietly. Facial scan is affected by a new hairstyle, facial hair, adding or removing a hat or glasses, variation in weight, movement, lighting conditions, and loud clothing. The iris-scan is affected by the wearing of glasses, too much movement of the eye or head, and contact lenses. Glasses and too much head or eye movement can affect the eye retina-scan. The finger-scan is affected by a dry, cold, or oily finger, extreme humidity, finger angle and pressure during placement, wear of fingerprint and cuts. The hand-scan is affected by change in weight and swelling joints. (International Biometric Group 2002)

Biometric data can change overtime, fingerprints tend to wear out and this process is increased with the use of household detergents and age. Children under six years are not able to supply a fingerprint. Children’s facial features tend to change as they increase in age, and adult’s facial features tend to change as they move into old age. The iris and the retina tend to change due to illness. (Ministry of Interior and Kingdom Relations, 2005)

Biometric Human identification, implementation has taken place in terms of passports in the Netherlands. However, security has been breached quite quickly and the Dutch Government is in the process of solving such a problem. (Markoff, 2006) 

The other implementation under going trial is the implantation of the RFID under the skin in the human body. (BBC News, 2004)



![image](https://github.com/olivemckenzie2003/olivemckenzie2003-RFID-IN-THE-ELECTRONIC-PAYMENT-/assets/115945473/6fd76da9-b8b6-4ce7-9179-22363b7eeb27)




