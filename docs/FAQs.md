# FAQs

### How can I configure my AWS credentials in my terminal?
In the left bar of the Workshop Studio, click on “Get AWS CLI credentials” and copy and paste that into your terminal.

### What region should I use?
Your account will be using us-west-2, which has access to the Bedrock base models.
Keep this in mind when working with AWS samples, as you might need to change the region to match us-west-2.

### What should I use for my frontend?
We recommend using Streamlit to make fast UIs. Here are some useful resources that we suggest exploring: [Streamlit Tutorials](https://docs.streamlit.io/knowledge-base/tutorials).

### How can I debug or see what’s going on with the resources I created?
You can use [AWS CloudWatch](https://aws.amazon.com/cloudwatch/) to check all the logs that come from different AWS services. When you’re stuck going to CloudWatch and inspecting the logs helps you a lot.

# Common Mistakes

### Extra Spaces

Having an extra space in AWS command parameters can lead to unexpected issues in your AWS services, which may be difficult/time-consuming to debug. AWS commands rely on having precise syntax, so even just one extra space can cause misinterpretation. To avoid headaches, always double check all the values and properties that you pass into AWS commands and methods. This way, you cam eliminate the time you spend debugging the issues caused by it.

