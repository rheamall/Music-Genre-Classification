# Music Genre Classification

In today's digital music landscape, personalized content is key to engaging users and driving customer satisfaction. Various music streaming platforms rely heavily on accurate music genre classification to enhance user experience through curated playlists and personalized recommendations. Accurate genre classification thus has a significant impact on various business metrics, including content discoverability and retention rates.

This project leveraged Convolutional Neural Networks (CNNs) to accurately classify music genres based on log-transformed Mel spectrograms obtained via the GTZAN dataset. CNNs, which are space-invariant, generally cannot be applied to images which contain meaningful axes; however, with a custom CNN architecture taking into account the time and freqeuncy components of the spectrograms separately, the model achieved a test accuracy of 92.66% - an improvement from the 87.37% achieved by traditional CNN models - demonstrating the effectiveness of this approach. 

### Business Relevancy 

My approach offered an innovative solution for accurate music genre categorization, thus aiding in the improvement of key business outcomes such as:
- Enhanced User Experience: More accurate music genre categorization enables better playlist curation, ensuring that users are served the content they like and prefer, keeping them engaged for longer periods.
- Improved Recommendations: With precise genre classification, recommendation algorithms can offer more relevant content, increasing user satisfaction.
- Operational Efficiency: Since the use of this model eliminates the need for manual categorization, it improves operational efficiency and costs.

### Future Avenues

**Multi-Genre Classification:** This project considered 4 music genres; Future works could consider expanding the model to classify songs that span multiple genres, which can provide more nuanced recommendations and playlist curation, further enhancing user engagement.

**Real-Time Genre Classification:** Future works could explore real-time genre classification, allowing streaming services to adapt to user preferences on the fly. This could lead to more dynamic and responsive user experiences.

**Cross-Domain Applications:** The architecture could also be adapted to other domains such as speech recognition, offering broad utility across various industries.

**Scaling:** The training dataset used was small, yet the accuracy of the model was very good. This approach is viable for integration into large-scale music platforms, allowing for highly accurate genre detection and categorization.

### Conclusion
By carefully considering the unique characteristics of Mel spectrograms, I developed a CNN model that not only achieved high accuracy but also aligned closely with business needs for improved user experience, operational efficiency and customer retention. The project highlighted the usefulness of innovative deep learning architectures in enhancing music genre classification. As music streaming platforms continue to grow, the ability to accurately and efficiently categorize music will remain a critical factor in driving user satisfaction and business success. 

#### Academic Project Credits
This project was part of an individual academic assignment given under the LSE ST456 course (2024); my work achieved the mark of **Distinction** in the assignment.
