# PuTTYgen UI Redesign

**Note**: This is a class project collaborated with two other members.

## Background

New users of public-key cryptography are often students who are using Github or Amazon Web Services (AWS) for the first time. When trying to generate keys, online instructions are command-line based and do not help users understand the purpose of the keys generated.
 
On Windows, PuTTYgen, also known as the PuTTY Key Generator, generates pairs of public and private keys to be used with PuTTY, PSCP and other authentication agents. It can generate RSA, DSA, ECDSA, and ED25519 keys. However, its user interface is not very user-friendly, so it is not much more usable than command-line tools.

## Major Issues

1.No clear order of actions

As you can see from Figure 2.1, there are a many options available in the UI; however, there is no clear order for which parts to use at any given time. For example, a user who is only trying to load a key is still given options for the type of key to generate, even though those are not meaningful.

2.Confusing icon

The desktop icon for PuTTYgen appears to be a PC from the early 90’s with a key and a lightning bolt. For most users, this icon simply points out that PuTTYgen is software that has not been updated recently. For some, it may appear to be malware.

3.No macOS version

After being available for so many years, PuTTYgen still does not have a macOS version. The most popular computers for new college students are Macs. We were unable to find any macOS key generating app with a GUI. If macOS users are not comfortable on the terminal, they have no equivalent substitute for PuTTYgen.

4.No explanation for key options

There are several types of keys that users can choose to generate. For some types of key, users can select the key size. However, there is no explanation to help users select the correct key type and key size.

For example, when users run PuTTYgen they will see options under “Parameters”: RSA, DSA, ECDSA, ED25519, SHA-1(RSA). However, there are no explanations of each type of key or the security strength of each. The default choice is: “Generate” – “RSA” – “2048”. If users really want to know the security features of each algorithm, they will have to read through the whole documentation or find external sources, which is very time-consuming.


5.Unclear purpose of generated keys

There are no scenarios associated with key generation -- generation of private and public key pairs is not followed by clear instructions on how to use the keys. For example, when a student wants to use the key pair to access an AWS server, there are no interfaces that can guide the student to make that happen. Also, after generating the key, there are no guidelines to help users to use and manage the keys. Users would have a clearer path to using their keys if common next steps were presented on screen.

6.UI looks ancient

The current UI simply looks designed for Windows 95. It is not aesthetically pleasing or intuitive. Users trust a design more when it conforms to modern design standards, so the current PuTTYgen will not be trusted.

## Project Objective

Our project aims to solve the issues listed above in the current version of PuTTYgen. We are focused on these two objectives:

- Create an aesthetically pleasing design to help students make the right decision quickly while knowing more about the advantages and disadvantages of each option. 

- Provide scenario-based guidelines to help users to better understand and use the tool.

## Solutions

- Adding brief explanations to each of the key options, including its security performance and possible trade-off.

- Adding links to related to user cases.

- Improving the visual aesthetic in the new UI to make it more intuitive for users.

## Redesign Progress
Phase I of our project has been completed, if you're interested in seeing our latest design, please contact us.










