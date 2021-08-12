 Smart-Customer-help-desk-Chat-Bot
# Intelligent Customer Help Desk with Smart Document Understanding

This repository contains the project report and the Node-Red flow of the chatbot developed using various IBM Watson Services for backend and Node-Red for UI. The typical customer care chatbot can answer simple questions, such as store locations and hours, directions. When a question falls outside of the scope of the pre-determined question set, the option is to tell the customer the question isn’t valid.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems. So unless and untill customer specifically asks for a customer representative the bot will try to solve all your queries.

To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries. Then using Watson actions as webhook, Watson Discovery can be integrated with Watson assistant. Finally using Node-Red, Watson assistant can be integrated with a web UI. This UI can then be used to connect with Watson assistant and chat with it.

View Demo Here!
Node-Red Dashboard: https://node-red-tvswk.eu-gb.mybluemix.net/ui/
