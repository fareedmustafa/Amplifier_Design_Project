# Amplifier_Design_Project
A three-stage BJT amplifier (CC-CE-CC)} achieving a voltage gain of 50%±10% and a robust output swing

Introduction
This report aims to thoroughly detail the development, deployment, and evaluation of a multistage amplifier utilizing multiple Bipolar Junction Transistors (BJT). The focus will be on adherence to specifications throughout the design process, ensuring the amplifier's performance meets the desired technical criteria. Additionally, the report will cover the testing procedures undertaken to validate the functionality and reliability of the amplifier under various conditions, demonstrating its capability to fulfill the established requirements.

Requirements
The following requirements are necessary to be met for the amplifier to be fully functional.

Power supply: +𝟏𝟎𝑽 relative to the ground;
• Quiescent current is drawn from the power supply: no larger than 𝟏𝟎 𝒎𝑨;
• No-load voltage gain (at 1 𝑘𝐻𝑧): |𝑨𝒗𝒐| = 𝟓𝟎 (± 𝟏𝟎%);
• Maximum no-load output voltage swing (at 1 𝑘𝐻𝑧): no smaller than 8 V peak to peak;
• Loaded voltage gain (at 1 𝑘𝐻𝑧 and with 𝑅𝐿 = 1 𝑘Ω): no smaller than 𝟗𝟎% of the no-load
voltage gain;
• Maximum loaded output voltage swing (at 1 𝑘𝐻𝑧 and 𝑅𝐿 = 1 𝑘Ω): no smaller than 4 V peak
to peak;
• Input resistance (at 1 𝑘𝐻𝑧): no smaller than 𝟐𝟎 𝒌𝜴;
• Amplifier type: inverting or non-inverting;
• Frequency response: 20 Hz to 50 kHz (−𝟑𝒅𝑩 response);
• Type of transistors: BJT;
• Number of transistors (stages): no more than 3;
• Resistances permitted: values smaller than 𝟐𝟐𝟎 𝒌𝜴 from the E24 series;
• Capacitors permitted: 𝟎. 𝟏 𝝁𝑭, 𝟏. 𝟎 𝝁𝑭, 𝟐. 𝟐 𝝁𝑭, 𝟒. 𝟕 𝝁𝑭, 𝟏𝟎 𝝁𝑭, 𝟒𝟕 𝝁𝑭, 𝟏𝟎𝟎 𝝁𝑭, 𝟐𝟐𝟎 
• The output voltage must be free from distortions (clipping, etc.) in all test conditions.
• The source resistance, 𝑅𝑠, must be 600 Ω for all tests

Amplifier Design
To meet the outlined specifications, an amplifier featuring a design consisting of a Common Emitter (CE) stage followed by two Common Collector (CC) stages was selected. This configuration, referred to as CC-CE-CC, was chosen for its ability to combine the advantages of both configurations, optimizing performance across different parameters. The Common Emitter stage is known for its high voltage gain, making it an excellent choice for the initial stage of amplification. Following this, the Common Collector stage, often known as emitter follower, are utilized for their ability to provide a high input impedance and a low output impedance. The design integrates these stages to achieve a balanced amplification system, capable of delivering high signal amplification in line with the other requirements set forth.
