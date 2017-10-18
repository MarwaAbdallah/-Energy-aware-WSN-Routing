# Welcome!

Here is a brief description of the 2 reports I prepared for my grad courses at Université de Montréal.
They are in french

The first one deals with Android's security , while the second one discusses Wireless sensor Networks and energy-aware L3 protocols.

The targeted audiences are grad students, not familiar with these new topics but with a concrete IT background.

# Android Security: Threaths Models and detection strategies

*Report: AndroidSecurity.pdf*

My teammate for this report is Théophile Henri.

After the introduction, we start by presenting the architecture of an application, which is the malwares' main point of entry.
Then, we expose the upstream security mechanisms: from the app markets, to the sandboxing and use of permission within the app and device. 
Next we introduce Google's payment system. In particular, we cite a couple proof of concept attack exploiting the legitim app's developer lack of rigour in the verification of the signature process.
The following section presents the main threats and their propagation vector.

Section VI presents the malware analysis and detection process. This is a very difficult problem and several approachs are extensively studied in the litterature and applied by Google and anti-malware companies.
We briefly present the hope brought by artificial intelligence: deep and machine learning. 
We finish by concluding.



# Energy Aware Routing methods for Precision Agriculture

They are both provided in the PDF format.

*Presentation (slides): WSN_Presentation.pdf*

*Report: WSN_Report.pdf*

I start by presenting the Precision Agriculture, it's current challenges and the introduction. Then, I present the sensor and Wireless Sensor Networks.

In this particular contexts, sensors are deployed usually in huge agricultural fields to send various non time critical data (humidity, pH....). The lifetime of the sensor depends on the lifetime of it's battery without any recharging, in most use cases.

In the next section, I present the current mechanisms aiming to reduce the enrgy consumptions and reach the best *energy efficiency*. This is the ratio of the total quantity of sent data to the total energy consumption.


These techniques varies and involves active research in : the sensor's positionning strategies in a field, L7 to L3 energy saving protocols and mechanisms.

In particular, we present IP level energy aware protocols, *LEACH* being the most cited one in the litterature





Good Reading!
