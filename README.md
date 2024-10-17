<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->


Pet Detector

Final project for the Building AI course

Summary

Pet Detector is an AI-based app that identifies whether an animal in an image is a dog or a cat based on their physical characteristics such as height, weight, and body length. This solution helps quickly classify pets in environments such as animal shelters or vet clinics.

Background

Distinguishing between dogs and cats can be challenging, especially with mixed breeds or overlapping physical characteristics. This problem is common in environments where many animals are handled, such as animal shelters or vet clinics. Personally, I am motivated by the idea of using AI to assist pet enthusiasts, volunteers, and professionals in identifying pets more easily and accurately. This topic is important for improving animal welfare and efficiency in shelters.

This is how you make a list, if you need one:

	•	Difficulty in identifying mixed breed pets
	•	Reducing manual effort for animal classification in shelters or clinics
	•	Providing a fun, educational tool for pet enthusiasts

How is it used?

The solution is used in environments such as animal shelters, veterinary clinics, or by pet enthusiasts at home. A user can upload or take a picture of a pet, and the app will identify if the pet is a dog or a cat based on the animal’s physical characteristics. The system can also predict the likelihood of the pet belonging to a certain group based on its measurements.

<img width="384" alt="image" src="https://github.com/user-attachments/assets/4ce75132-72c6-4b2f-93ee-5a159637090c">

Data sources and AI methods

The project depends on labeled image datasets of cats and dogs, as well as their corresponding physical measurements such as height, weight, and body length. Public datasets from shelters or pet research organizations can be used. The AI techniques used include convolutional neural networks (CNNs) for image classification and logistic regression for binary classification based on the physical data.

AI Method	Description
CNN	Classify images of pets
Logistic Regression	Binary classification of pets using measurements

Challenges

The project may not handle edge cases well, such as pets with overlapping characteristics, low-quality images, or animals with physical anomalies. It won’t classify specific breeds, and data quality could vary regionally, making the model less reliable in some regions.

What next?

The project could grow by adding features to classify breeds or detect health issues based on physical characteristics. Developing a mobile app that allows users to snap a photo and receive insights on their pet would be a natural next step. Collaboration with veterinarians or animal welfare experts would help in refining the solution.

Acknowledgments

	•	Convolutional Neural Networks (CNN) models by open-source contributors on platforms such as TensorFlow and PyTorch.
	•	Inspiration from existing pet recognition apps and animal welfare data platforms.
	•	Data sourced from open datasets available from animal shelters and pet research institutes.
For example: Sleeping Cat on Her Back by Umberto Salvagnin / CC BY 2.0

This version incorporates your idea into the structure of the markdown template for the final project.
