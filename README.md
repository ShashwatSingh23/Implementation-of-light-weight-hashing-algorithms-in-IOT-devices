**Implementation of light weight hashing algorithms in IOT devices**

**Abstract:**

In this modern world, technological advancements have grown more complex and at the same
time have made user lives easier and easier. In this broad term of technology exists a very
important factor applied to almost all technological products which is the security of the
product or service. Cryptography is the way of ensuring safety during communication and
while accessing the device or service.
For smaller devices, the same encryption methods are not applicable or too
resourceconsuming because they have limited battery and storage unlike mainframes or even
at least the latest portable computers. Thus, lightweight hash function takes into consideration
the limited capacity and computational capabilities and resources provided by these systems.
The need for lightweight (that is, compact, low-power, low-energy) cryptographic hash
functions has been repeatedly expressed by professionals, notably to implement
cryptographic protocols in RFID technology. At the time of writing, however, no algorithm
exists that provides satisfactory security and performance.
The ongoing SHA-3 Competition will not help, as it concerns general-purpose designs and
focuses on software performance. This paper thus proposes a novel design philosophy for
lightweight hash functions in order to minimize memory requirements.
This paper explores the implementation of lightweight hash functions for Internet of Things
(IoT) devices. As IoT devices often have limited processing power, memory, and energy
resources, traditional hash functions may not be suitable for use in these devices. Therefore,
the paper proposes the use of lightweight hash functions that have been specifically designed
to operate efficiently on IoT devices. The paper describes the characteristics and design
principles of lightweight hash functions, and presents a comparative analysis of several
popular lightweight hash functions. Additionally, the paper discusses the practical
implementation of lightweight hash functions on IoT devices, including the challenges and
considerations that need to be taken into account. The results demonstrate that lightweight
hash functions can provide an effective solution for securing IoT devices while minimizing
resource consumption. 

**Existing System Issue:**

1. Security: One of the most significant issues with IoT devices is security. Many IoT
devices are vulnerable to cyber-attacks, which can result in data breaches, theft of sensitive
information, and even physical harm to individuals. By implementing hash functions, IoT
devices can enhance their security by providing a more secure and efficient way to store and
transmit data.
2. Data Integrity: Another issue with IoT devices is the potential for data corruption or
loss due to errors in transmission or storage. Hash functions can provide a way to verify data
integrity by providing a unique fingerprint for each piece of data. This fingerprint can be used
to verify that the data has not been tampered with or corrupted.
3. Resource Constraints: IoT devices typically have limited resources, including
processing power, memory, and battery life. Hash functions can be designed to be lightweight
and efficient, making them ideal for use in IoT devices with limited resources.
4. Compatibility: IoT devices often operate on different platforms and use different
communication protocols, making it difficult to implement a standardized security solution.
Hash functions can be implemented on a variety of platforms and can be used with a wide
range of communication protocols, making them a versatile and flexible solution for IoT
devices.
By addressing these existing system issues, the implementation of hash functions for IoT
devices can help improve the security and reliability of IoT devices and enable the
development of more robust and reliable IoT applications.

**Algorithm Used:**

The Quark hashing algorithm was designed as a cryptographic hash function that is highly
resistant to collision attacks. The algorithm operates on a message input and produces a
fixedsize hash output, which can be used for data integrity verification, authentication, and
other security applications.
After extensive analysis and testing, the Quark hashing algorithm has been shown to have
several important security properties, including resistance to preimage attacks, second
preimage attacks, and collision attacks. In other words, it is highly unlikely for an attacker to
find two different messages that produce the same hash value (collision), or to find a message
that produces a specific hash value (preimage attack) or to find a second message that
produces the same hash as a given message (second preimage attack).
The Quark hashing algorithm is also designed to be efficient and computationally lightweight,
making it suitable for use in a wide range of applications where secure hash functions are
required. It has been implemented in several software libraries and frameworks and is widely
used in various security applications.
Overall, the conclusion of the analysis and testing of the Quark hashing algorithm is that it is
a highly secure and efficient cryptographic hash function that provides strong protection
against a range of attacks.

**Results:**
The Quark hash algorithm produces a fixed-length output of 32 bytes (256 bits). This output is
considered secure and is used for a variety of applications, including cryptocurrency mining,
digital signatures, and authentication protocols. The output of the Quark hash algorithm is
also uniformly distributed, meaning that every possible output is equally likely to be
generated, which is an important property for cryptographic algorithms. Overall, the Quark
hashing algorithm is considered a secure and efficient cryptographic hash function.

**Comparative Study:**

We compared the performance of quark hashing with several other hash functions, including
MD5, SHA-1, SHA-2, and SHA-3. The results showed that quark hashing performed better than
MD5 and SHA-1 in terms of collision resistance and was comparable to SHA-2 and SHA-3.
However, quark hashing was found to be slower than SHA-2 and SHA-3 in terms of
computation speed.
In this study, they compared the performance of quark hashing with BLAKE2 and SHA-3. The
results showed that quark hashing performed better than SHA-3 in terms of collision
resistance. However, quark hashing was found to be slower than SHA-3 in terms of
computation speed. 

**Conclusion:**

The Quark hashing algorithm was designed as a cryptographic hash function that is highly
resistant to collision attacks. The algorithm operates on a message input and produces a
fixedsize hash output, which can be used for data integrity verification, authentication, and
other security applications.
After extensive analysis and testing, the Quark hashing algorithm has been shown to have
several important security properties, including resistance to preimage attacks, second
preimage attacks, and collision attacks. In other words, it is highly unlikely for an attacker to
find two different messages that produce the same hash value (collision), or to find a message
that produces a specific hash value (preimage attack) or to find a second message that
produces the same hash as a given message (second preimage attack).
The Quark hashing algorithm is also designed to be efficient and computationally lightweight,
making it suitable for use in a wide range of applications where secure hash functions are
required. It has been implemented in several software libraries and frameworks and is widely
used in various security applications.
Overall, the conclusion of the analysis and testing of the Quark hashing algorithm is that it is
a highly secure and efficient cryptographic hash function that provides strong protection
against a range of attacks. 
