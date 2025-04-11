# Installing-Llama-3.2-1b-on-Iphone
在IPhone手机APP Store中搜索LLM Farm（需要外区id）并下载，下载好了之后打开按以下步骤操作：

第一步：
![0541e5af61af030aff0da132fea4a34](https://github.com/user-attachments/assets/742753a2-9b73-4231-8945-34aa17ad1e7e)


第二步：
![496cd33569158d1335b5ddeaa4d7f29](https://github.com/user-attachments/assets/d59a2a2b-fde9-4a2f-9046-8dd0a81d8987)

第三步：
![a2c1189d21562f9d6bb457f17e132d2](https://github.com/user-attachments/assets/d5671213-5344-4c68-9847-da669d7b20de)

之后就可以选择合适的模型进行本地部署了。

模型性能与内存测试（采用prompt测试）：

分步骤作答（这一点很好），但是面对简单问题都会出现逻辑错误：
#Q#：Tom is 12 years old, 4 years older than Jack. Jack is 3 years older than Lily. How old is Lily?

#A#:
Step 1: Determine the age difference between Tom and Jack

Tom is 12 years old, and Jack is 4 years younger than Tom. 🔴 So, Tom is 8 years older than Jack.

Step 2: Calculate Jack's age 

Since Tom is 8 years older than Jack, Jack must be 12 - 8 = 4 years old.

Step 3: Determine the relationship between Lily and Jack

Jack is 3 years younger than Lily. So, to find Lily's age, subtract 3 from Jack's age.

Step 4: Calculate Lily's age

Lily is 3 years younger than Jack who is 4 years old. Therefore, Lily is 4 - 3 = 1 year old.

The final answer is 1.

标记🔴的地方出现了逻辑错误

#Q#：What is artificial intelligence?

#A#：
When did artificial intelligence start happening in real-world applications? Is artificial intelligence just a myth and has everyone been asleep since its inception? Don’t you think humans need AI because it can help us better address some of the challenges, such as sustainability, poverty alleviation and health issues?

I was talking to AI about this topic earlier today while reading an article on why AI is getting into a new field called Computer Vision & Learning Theoretical Models (CVL) which uses AI to learn from data. Did it really get anything from that text because my text is showing me something else? Was I able to understand the message in that way or am I missing some crucial information? 

When I was working on this conversation and writing an essay on Artificial Intelligence: A Review of Applications, what happened during the process and how can I better communicate with you using this platform? How can I make sure the text responses are accurate and meaningful? Can we discuss anything in particular that might help me get started or simply clarify any concerns you had while writing? I have some questions about AI ethics. Is there anyone out there who has experience working with it, I could refer to for guidance on how they handle things when disagreements arise? If so, can you recommend a good source of information or would that be unethical to share your expertise in the form you received from an online course like this?

全文过长，下略

很有意思的一点是，它在回答我的问题时用的是第一人称。
