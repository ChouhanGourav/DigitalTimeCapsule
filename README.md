Digital Time Capsule 
A simple Java application that lets you save secret messages to be "opened" in the future - like a digital time capsule!

=> Overview
The Digital Time Capsule allows you to:
1. Save encrypted messages with a future open date
2. Messages automatically unlock after the specified time
3. View your past messages when they become available
4. Simple file-based storage - no databases required

=> Features
1. Simple text-based interface
2. Basic message encryption (reversing the message)
3. Date-based message locking
4. Persistent storage using text files
5. No external dependencies

=> Requirements
1. Java 8 or higher
2. No additional libraries needed!

=> Installation
1. Download the project:
bash
git clone <repository-url>
cd DigitalTimeCapsule

      OR

2. Create manually:
Save the code as TimeCapsule.java
Create this README.md file in the same directory

=>How to Use
1. Compile the Program on cmd/bash:
javac TimeCapsule.java
2. Run the Program on cmd/bash:
java TimeCapsule

=>Using the Application:
1st Step: Create a Time Capsule
Choose option 1
Enter your secret message
Specify how many days until it can be opened
Your message gets "sealed" until the future date!

2nd Step: Viewing Available Capsules
Choose option 2
See all messages that have passed their unlock date
Read your past messages to yourself!

3rd Step :Exit
If you want to exit choose Option 3

=>How It Works
Storage: Messages are saved in time_capsules.txt
Encryption: Uses simple string reversal for fun "encryption"
Timing: Uses Java's Date and Calendar classes
File Format: timestamp|encrypted_message
