# AI-Powered-Call-Center-Local-Deploy:FreeSWITCH+Java+SpringBoot+VUE
AI-enhanced call center system, AI-Powered contact center system, based on FreeSWITCH, Java, Python, SpringBoot, VUE and other technology stacks, can be connected to mainstream TTS, ASR products, can be deployed locally, can build automatic outbound call system, automatic inbound call robot system, agent assistance system;Can work with online customer service and work order system to realize unified queuing of text messages and voice calls!!!!!!!!

## 😄We firmly believe that only when the software is used can it bring value to users and allow itself to iterate
## 😄Sustainability: It has been continuously iterating since 2014, and the members are very experienced and long-term

# Our goal
Committed to becoming: a global leader in large-model call center systems, large-model inbound robots, large-model outbound robots, and intelligent call center systems!

## 📫 How to reach us:
- 官方WeChat:freeipcc
- Whatsapp：Click <a href="https://api.whatsapp.com/send?phone=+8615700176897&text=Hello">WhatsApp</a> to Chat
- Skype：https://join.skype.com/invite/rVbQH1igkQwV
- Skype UserID：live:.cid.fedb411de91d9b
- Email:leehear@gmail.com 

## 2025.06.01 latest demo link enjoy😄:
1. Telephone/online customer service:
http://124.220.48.38:8822/cc
 (demo123/demo123@Abc)
 
2. Work order:
http://124.220.48.38:80
 (demo/123456)

注意：如果页面打不开，是因为demo页面正在频受DDo5攻击，目前我们正报警处理，还请用户谅解。可直接加我们联络方式进行沟通。
![image](https://github.com/user-attachments/assets/a87bf18e-36c6-42d0-b4ca-e01c9c9c1491)

3，Demo Videos：download the MP4 files。

## Development language: Java+Python+VUE
# Overview of the architecture of the LLM Call Center
![image](https://github.com/user-attachments/assets/25a232ec-4053-4097-b5db-09052a0cfcf7)

# FreeIPCC's vision and basic functions

## Vision:
Our vision is to create an open, flexible and powerful open source call center solution that enables global enterprises and organizations, regardless of size, to easily build and operate their own customer service systems.

We believe that by sharing source code, promoting technological innovation and collaboration, we can break the barriers of traditional call centers and benefit every developer, business owner and even end user.

Our goal is not just to provide a tool, but to build an ecosystem that allows users from different backgrounds and different needs to jointly explore, customize and optimize the functions and experience of the call center, and ultimately promote the progress and development of the entire customer service industry!!

## Basic functions:
1. Multi-channel access: Supports multiple customer communication channels such as phone, SMS, social media, email, web chat, etc., to achieve seamless docking and unified management of customer needs.
2. Intelligent routing: Based on preset rules or AI algorithms, automatically assign customer requests to the most appropriate customer service representative or self-service module to ensure that customer issues are handled promptly and professionally.
3. IVR (Interactive Voice Response) System: Provides flexible voice menu design to guide customers to complete common operations such as inquiries and repairs by themselves, reduce the pressure on manual seats, and improve service efficiency.
4. Seat Management: Provides comprehensive seat management tools, including real-time monitoring, recording playback, work order management, performance statistics, etc., to help managers optimize team operations and improve service quality.
5. CRM Integration: Supports seamless integration with mainstream CRM systems, automatically synchronizes customer information, realizes comprehensive integration and utilization of customer data, and provides data support for personalized services.
6. Data Analysis and Reports: Built-in powerful data analysis engine, automatically generates various service reports, such as call volume statistics, customer satisfaction surveys, service efficiency analysis, etc., to provide data basis for decision-making.
7. Open API and plug-in extension: Provides rich API interfaces to support third-party developers to expand functions or customize development based on our platform. At the same time, we will also actively maintain a plug-in market and include high-quality plug-ins for users to choose from.
8. Cloud-native architecture: Adopting cloud-native architecture design, it supports rapid deployment, elastic expansion and automatic operation and maintenance, reduces users' IT costs and maintenance difficulties, and ensures high availability and security of the system.
9. Highly configurable: Provides an intuitive configuration interface, allowing users to adjust system parameters and optimize workflows according to their needs without programming, and achieve rapid customization and deployment.
10. Community support and ecological co-construction: Establish an active open source community to encourage users to share experiences, propose requirements, contribute code, and jointly promote the continuous development and improvement of the project. We believe that through the power of the community, our open source call center will continue to evolve and become a leader in the field of customer service! 
    
# Features List

## Connect with telephone operator

1. Gateway management: Connect to the operator's voice gateway for incoming and outgoing calls
2. Gateway registration: Voice gateway registration
3. Gateway multiple lines: Currently, the main connections are T1 (30B+D) lines, SIP lines, FXO analog lines, or other PBX third-party devices that support SIP.
4. Blacklist: Add certain incoming call numbers to the blacklist

## Call center incoming call function

1. Call routing mode: Select the gateway and line for routing according to the dialing plan
2. Caller-based routing: Routing according to the caller's number
3. Callee-based routing: Routing according to the called number
4. DTMF-based routing: Routing according to DTMF
5. ASR-based routing:	ASR identifies the user selection for routing
6. Database interaction-based routing: Call processing and routing based on the collected information through database interaction
7. Skill group-based routing: Routing by skill group
8. Priority-based routing：Routing according to user priority
9. Secondary routing：Perform secondary new routing based on a certain number of queues
10. Time-based routing: Routing based on time (time of day), date (day of week) and holidays
11. IVR voice files: Welcome message files, etc.
12. TTS: Welcome message files can be intelligently broadcasted through TTS
13. ASR:Support user ASR recognition into text information
14. IVR editing:	IVR visual process editing, support menu, time and date, HTTP interface, voice broadcast, route selection, assignment, conditional judgment, intelligent dialogue, DTMF collection, hang up and end
Agent selection strategy	Agent selection strategy: longest waiting time, longest average waiting time, minimum number of answered calls, shortest call time, random selection, etc.
15. Agent call connection:	Agent general functions: sign in, sign out, busy, ready, hang up, outbound call
16. Agent name notification: function	Hear the agent's name prompt when transferring the call
17. Multi-party conference:	Support multi-party conference
18. Team leader function:	Monitor, force insertion, and force removal
19. Real-time voice stream push: Support push of call voice stream to third party
20. Call mute:	Mute the agent
21. Call hold:	The agent holds the call
22. Call transfer:	The agent transfers the call to other agents, queues, external lines, etc.
23. Call consultation:	The agent consults other agents and resumes the call
24. Call status push:	Push the call status
25. Incoming call pop-up screen:	Monitor incoming call messages, pop up the browser screen, and bring out the required information
26. Recording:	Supports WAV, MP3, dual-track recording, supports recording upload
27. Satisfaction evaluation:	Supports satisfaction evaluation
28. Inbound call report: Detailed call report

## Call out function
1. Predictive outbound calls:	After the user is connected, he/she will be transferred to an idle seat
2. Outbound call tasks:	Creation and deletion of outbound call tasks
3. Outbound call strategies:	Setting outbound call strategies: outbound call time, re-call strategy, outbound call script settings
4. Outbound call data sources:	Data source association with outbound call data
5. Outbound call monitoring:	Outbound call task monitoring
6. Outbound call reports:	Outbound call report data
7. Call details:	Call details (incoming/outgoing call time, queue entry time, main/called ringing time, answering time, hang-up time, recording time, call duration, call duration, etc.)
8. Call bill push:	Pushing call records to third-party systems

## AI intelligent functions
1. Intelligent knowledge base:	Support document, QA import, document vectorization, full-text search, vector search, dynamic addition of related questions
2. AI Agent intelligent process:	Support advanced visual process arrangement, can be based on actual business, each intelligent node flow, support priority knowledge base search, and then optimize the output of the large model
3. Intelligent inbound and outbound: IVR	Call IVR, support access to intelligent digital employees, docking with large models, dynamic IVR, intelligent flow, support HTTP method, access to third-party large model NLP
4. Online customer service:	H5 online customer service (supports intelligent Q&A through background knowledge base and large model)

## Report functions
1. Agent status table:	Record agent login, idle, busy, answering, outbound calls, etc.
2. Agent statistics report:	Query agent statistics by time
3. Outbound call task status:	View outbound call task status
4. Queue status:	View queue status

## Management function
1. User management:	Management of user accounts used to log into the system
2. Phone management:	IP extension phones registered in the system
3. Directory number management:	Extension number management
4. Menu management:	System menu management, different roles have different permissions to view different menu options
5. Role management:	User permission roles
6. Number pool management:	Multiple number collections
7. Skill group management:	Service attribute-related seat capability groups, with multiple seats in the group
8. Agent management:	Agent management
9. Skills:	Skills related to business attributes

## API function
1. CTI interface:	Sign in, sign out, busy, idle, after the call, answer, hang up, outgoing, consultation, transfer, forced insertion, forced removal, monitoring
2. Outbound call data import:	Batch import, outbound call data, mainly import outbound call numbers, outbound call items
3. Call record push:	Push real-time data after hanging up (incoming/outgoing call time, queue time, main/called ringing time, answer time, hang up time, recording time, call duration, call duration, etc.)
## Others
1. Cluster management:	Support FreeSWITCH cluster
2. Multi-database support:	MySQL、PostgreSQL、SQLServer、Oracle!

# Features List screenshot
![image](https://github.com/user-attachments/assets/ac90112f-311d-4ebb-8206-dff3ae643ee9)
![image](https://github.com/user-attachments/assets/ca05d14b-64f3-411f-9729-715f94f2c3b7)

# 我们坚信：软件只有被用起来，才能给用户带去价值，才能让自身产生迭代！
# 附：团队的开源呼叫中心系统FreeAICC（AI Call Center）的愿景与基础功能阐述
愿景：
我们的愿景是打造一个开放、灵活且强大的开源呼叫中心解决方案，赋能全球的企业和组织，无论规模大小，都能轻松构建并运营自己的客户服务体系。我们相信，通过共享源代码、促进技术创新与协作，能够打破传统呼叫中心的壁垒，让每一位开发者、企业主乃至终端用户都能从中受益。我们的目标不仅仅是提供一个工具，而是构建一个生态系统，让不同背景、不同需求的用户能够共同探索、定制并优化呼叫中心的功能与体验，最终推动整个客户服务行业的进步与发展！

基础功能：
1.	多渠道接入：支持电话、短信、社交媒体、电子邮件、网页聊天等多种客户沟通渠道，实现客户需求的无缝对接与统一管理。
2.	智能路由：基于预设规则或AI算法，自动将客户请求分配给最合适的客服代表或自助服务模块，确保客户问题得到及时、专业的处理。
3.	IVR（交互式语音应答）系统：提供灵活的语音菜单设计，引导客户自助完成查询、报修等常见操作，减轻人工坐席压力，提升服务效率。
4.	坐席管理：提供全面的坐席管理工具，包括实时监控、录音回放、工单管理、绩效统计等，帮助管理者优化团队运作，提升服务质量。
5.	CRM集成：支持与主流CRM系统无缝集成，自动同步客户信息，实现客户数据的全面整合与利用，为个性化服务提供数据支持。
6.	数据分析与报表：内置强大的数据分析引擎，自动生成各类服务报表，如通话量统计、客户满意度调查、服务效率分析等，为决策提供数据依据。
7.	开放API与插件扩展：提供丰富的API接口，支持第三方开发者基于我们的平台进行功能扩展或定制开发，同时，我们也将积极维护一个插件市场，收录优质插件供用户选择。
8.	云原生架构：采用云原生架构设计，支持快速部署、弹性扩展与自动运维，降低用户的IT成本与维护难度，同时保证系统的高可用性与安全性。
9.	高度可配置：提供直观的配置界面，让用户无需编程即可根据自身需求调整系统参数、优化工作流程，实现快速定制与部署。
10.	社区支持与生态共建：建立一个活跃的开源社区，鼓励用户分享经验、提出需求、贡献代码，共同推动项目的持续发展与完善。我们相信，通过社区的力量，我们的开源呼叫中心将不断进化，成为客户服务领域的佼佼者！

![image](https://github.com/user-attachments/assets/604a9a46-edc8-4a1f-9f94-a5021f178101)
![freeipcc14](https://github.com/user-attachments/assets/c1e5a412-6a38-48bc-bbad-2a129af562e7)
![image](https://github.com/user-attachments/assets/e7fcb31f-530b-4b96-a6e3-e90fb9f5db60)
![image](https://github.com/user-attachments/assets/52064c20-f502-423a-9546-b865aa2e11ff)
![image](https://github.com/user-attachments/assets/b68d242e-ca19-4806-b84c-11239ee2d8f6)
![image](https://github.com/user-attachments/assets/11367dfa-22d2-4976-8ec8-6e3c51b84e46)
![freeipcc15](https://github.com/user-attachments/assets/a9b20c37-2b29-4a92-b06a-af1fcc5c75ed)
![05-大模型呼叫中心-自助建工单-自助解决问题-拓扑简图01](https://github.com/user-attachments/assets/0b53f8b5-72f3-4f1f-82d4-cf50f60ad875)
![image](https://github.com/user-attachments/assets/8bfca84f-996f-4cb3-ae35-88918e99f8f7)
![image](https://github.com/user-attachments/assets/34ec0973-a012-47ae-b924-3d25a9c65c58)
![image](https://github.com/user-attachments/assets/dd5ef068-e4cc-48ba-aaa6-074f1eade244)
![image](https://github.com/user-attachments/assets/7889efb4-85e9-45b2-84a4-ea837dc6b7fd)
![image](https://github.com/user-attachments/assets/96c81618-9d85-4d32-9f9a-6719426b4640)
![image](https://github.com/user-attachments/assets/38877999-8119-4bb9-b280-4f0b26a06414)
![image](https://github.com/user-attachments/assets/5c3f7012-629a-4f4f-a5cf-f4ce72b9a095)
![image](https://github.com/user-attachments/assets/ecd3785c-499b-4c62-abea-eba066dd6daa)

## 🤔工单系统功能列表

![image](https://github.com/user-attachments/assets/b3579741-07f2-4f2d-936e-b97bfca38b17)
![image](https://github.com/user-attachments/assets/c4f7ccb6-02b9-4345-aa53-a1898b2db04c)

## 😄每一个用户，都有专属群支持：10人左右，响应更及时

下图是随机抽取的需求对接的群：

![image](https://github.com/user-attachments/assets/71abf504-db94-4618-ab35-725f5de8c8f8)
![image](https://github.com/user-attachments/assets/5dad75c9-432c-4284-b17c-f85211ffe341)

![image](https://github.com/user-attachments/assets/e28c4c61-9105-4461-ab68-988bcc14736c)

# 😄再次表达一下价值观：我们坚信，软件只有被用起来，才能给用户带去价值，才能让自身产生迭代！
