# Cyber-Armor-AI
1. Project Background and Description:
The internet has seamlessly integrated into our daily lives, becoming an indispensable component. Nonetheless, it has also opened doors for malicious actors to engage in activities such as phishing, often exploiting the evolving landscape of online vulnerabilities. While numerous techniques have been developed to detect phishing websites, the perpetrators have continually adapted their strategies to evade existing detection methods.
2. Project Scope:
In response to this ongoing challenge, we propose an innovative approach for detecting phishing websites that leverages the power of natural language processing (NLP) for information extraction, including recognition and tagging, and harnesses convolutional neural networks (CNNs) for document and image analysis. Our method goes beyond traditional detection approaches by examining content similarity and web similarity, thus enhancing the accuracy and effectiveness of phishing detection. This project aims to contribute to the ongoing efforts to combat online threats and protect users from falling victim to phishing attacks in an ever-evolving digital landscape.
3. High-Level Requirements
The new system must include the following:
 Intel I3 gen10 or AMD Ryzen 3
 Anaconda Navigator
 TensorFlow, Keras and some Packages
2
4. Use Cases
Delivery Companies:
Attackers send emails or text messages that appear to be from well-known delivery
companies claiming that a package is on its way or there's a delivery problem.
Payment Systems:
Attackers create fake websites that mimic the login pages of popular payment
systems. Unsuspecting victims are tricked into entering their payment details, which
are then captured by the phishers.
Global Internet Portals:
Malicious actors can sometimes use online advertising networks to display phishing
ads on search engines, websites, or social media platforms. Users who click on these
ads may be directed to phishing sites.
Social Networks:
Phishers create fake profiles that impersonate individuals, organizations, or trusted
entities. These profiles may appear convincing and are used to send phishing
messages or engage in deceptive activities.
5. Idea / Solution:
Phishing Detection using NLP and CNN:
To tackle the multifaceted nature of phishing attempts, we employed a cutting-edge
approach that combined Natural Language Processing (NLP) techniques with
Convolutional Neural Networks (CNN).
Utilize NLP to extract suspect URL from the dataset based on the provided
description. NLP allowed us to analyze and interpret text-based content, Retrieve
suspected URL from the filtered dataset, while CNN models were utilized for imagebased
phishing detection.
The synergy between these two techniques was crucial in comprehensively
addressing the diverse forms of phishing attacks encountered in practice.
3
Our technical toolkit included Python, TensorFlow, and Scikit-learn. Python served as our primary programming language, offering a rich ecosystem of libraries for data preprocessing and model development. TensorFlow provided a robust framework for training and fine-tuning our neural networks, while Scikit-learn offered valuable support for data preprocessing and machine learning tasks.
6. Dataset Description:
The features of our dataset are as follows:
 Having IP Address: If an IP address is used instead of the domain name in the URL, such as http://217.102.24.235/sample.html.
 URL Length: Phishers can use a long URL to hide the doubtful part in the address bar.
 Shortening Service: Links to the webpage that has along URL. For example, the URL http://sharif.hud.ac.uk/ can be shortened to bit.ly/1sSEGTB.
 Having @ Symbol: Using the @ symbol in the URL leads the browser to ignore everything preceding the @ symbol and the real address often follows the @ symbol
 Double Slash Redirection: The existence of // within the URL which means that the user will be redirected to another website
 Prefix Suffix: Phishers tend to add prefixes or suffixes separated by (-) to the domain name so that users feel that they are dealing with a legitimate webpage. For example http://www.Confirme-paypal.com.
