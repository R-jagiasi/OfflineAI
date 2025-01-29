## **OfflineAI**
Stay connected with AI capabilities through SMS—internet connectivity not required! (Contact us at +1(450)-990-6969) (Inspired by Aleem's innovative concept: Search the Internet without the Internet)

## **Inspiration**
OfflineAI was conceived with the aim to democratize AI technology for everyone, particularly targeting regions in developing countries where internet services are either unreliable or unavailable. Despite these connectivity challenges, mobile phone usage remains high, making SMS an essential tool for communication.

This project strives to narrow the digital divide, offering individuals in underprivileged areas the chance to utilize AI technologies for everyday communication and information retrieval. With OfflineAI, users can stay in touch with loved ones, seek information, and receive tailored suggestions, all without a dependable internet connection.

## **Functionality**
Users can interact with OfflineAI by sending an SMS to our dedicated number. This enables them to receive AI-generated replies directly via SMS without needing an internet connection. The service supports sending and receiving text, images, and unlimited queries, ensuring a robust and user-friendly experience.

## **Development Process**
The backbone of OfflineAI involves routing incoming SMS messages through Twilio to an AWS Lambda function. This function identifies the nature of each request and forwards it to the relevant API or service, like forwarding image requests to OpenAI's servers.

The content of the message is then processed by Co:here, a sophisticated natural language processing platform. Co:here’s algorithms analyze the text and generate a relevant response, which is subsequently sent back to the user through Twilio.

This innovative SMS-based AI service leverages cutting-edge technology to provide rapid, accurate, and personalized answers, making digital services accessible in even the most remote locations.

## **Challenges Encountered**
I faced several hurdles with the Twilio service, from trial authentication restrictions to our account being unexpectedly suspended. These issues required us to adapt quickly, setting up new accounts and finding solutions to keep the service operational.

## **Achievements**
I am particularly proud of how seamlessly the API interactions and serverless functions were implemented. The integration of Co:here and DALL-E worked flawlessly, enhancing my skills in handling XML responses instead of the typical JSON format.

## **Lessons Learned**
This project was an educational journey in server management and the intricacies of Twilio's API. I discovered the complexities involved with web loading and gained a deep appreciation for the capabilities of Co:here’s generative models. Additionally, the challenges of using Tailwind for styling were quite enlightening.

## **Future Directions for OfflineAI**
Looking ahead, I plan to expand OfflineAI’s features to include additional AI models and international capabilities. Implementing a translation feature is high on the agenda, which would necessitate backend support to manage message histories effectively.



## What's next for AccessAI

Add more models, and make it international. I want to be able to incorporate a translate button but I would need to host it on a database to retrieve the previous message. Lots to come.

