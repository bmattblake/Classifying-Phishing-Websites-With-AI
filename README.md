# Classifying-Phishing-Websites-With-AI

**The challenge we are addressing involves how we can effectively differentiate between legitimate websites and phishing websites.** In the modern digital landscape, users routinely use websites for a multitude of purposes; thus, online security is paramount.

Phishing is a form of cybercrime that entails building deceptive websites to deceive users into divulging sensitive information, engaging in harmful actions, or falling victim to fraudulent activities.

There are a few groups of people that fall under the umbrella of "stakeholders". This includes the following groups:

 - Internet Users: These are everyday users who access websites for a variety of purposes, from shopping to banking. They are at the forefront of this problem since they are the most likely to be a potential victim of phishing attacks.
 - Website Administrators: Those responsible for maintaining and securing websites. They aim to protect their platforms and user data from malicious activities.
 - Cybersecurity Experts: Professionals in cybersecurity who aim to develop strategies to combat cyber threats and protect individual's sensitive data.
 - Organization/Businesses: This encompasses any entity that operates online services, such as e-commerce platforms, banks, and social media networks. They have a vested interest in maintaining the trust and security of their online services to protect their brand and customers.

The importance of this problem boils down to the fact that phishing attacks have the potential to compromise sensitive personal and financial information, presenting a significant threat to individual security and privacy. Victims of phishing scams may experience identity theft, and unauthorized access to their financial accounts. From a business perspective, it’s important to preserve trust between themselves and potential consumers. When this trust is eroded due to security concerns, it could lead to hesitancy to engage in online commerce. It is important for solutions to start emerging in order to create a more safe and secure digital environment.

Phishing attacks have been on the rise in recent years. The Anti-Phishing Working Group, or AWPG, is a coalition of individuals such as cybercrime responders, investors, and law enforcement agencies that focus on eliminating identity theft and frauds that are the result of phishing and other similar cyber attacks. AWPG reported that in the third quarter of 2023, there were a total of 1,270,883 phishing attacks, a record number that made Q3 2023 the worst observed [1]. This illustrates the sentiment that phishing attacks are becoming much more commonplace on the Internet. As a result, we need to start leveraging tools such as AI and machine learning to help us in this endeavor.

Machine learning algorithms present a compelling solution in helping efficiently distinguish legitimate websites from phishing ones. This is not a simple solution, since the nature of this problem has different characteristics and anomalies depending on the malicious actor in question. However, there are obvious benefits to leveraging a machine learning algorithm. First, they excel at pattern recognition and thus can see subtle features and behaviors that may elude traditional rule-based systems. In this case, this may come in URL structure, content analysis, and user behavior. They are also incredible at adapting and scaling to the dataset that we provide. In our case, we have a fixed number of cases, but in theory, it can handle the size and complexity of an extremely large dataset. Finally, the efficiency that it has helps with the processing and analysis of web data, allowing us to come to actions or conclusions at a more rapid pace. One main downside to these models is concerns about data quality. Machine learning models are highly dependent on the quality of the data it is trained on. If the representativeness of the data is not of good quality, it can result in skewed or inaccurate predictions.

There are a few research questions that we have at the start of our project:

1. Can machine learning models effectively differentiate between legitimate and phishing websites based on the URL and web page features?
2. What features are the most important in distinguishing between legitimate and phishing websites?
3.  How can this model be optimized so that it can keep up with phishing tactic development over time?
4.   What are the practical implications and limitations of implementing machine learning-based phishing detection in the real world?
