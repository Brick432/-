# 三、系统上线
系统上线是开源安全治理的重要一环，通过将系统投入实际使用，为后续试点及最终开源风险治理工作提供能力支撑，验证项目运营方案在实际实施过程中的可行性，通过系统使用过程中发现的问题及时对运营方案进行调整，保证运营方案能够有效的实施和运行。

## 3.1 平台部署上线
### 3.1.1 系统发布
为了让用户能够正常访问并使用系统，需要将系统发布在企业内部指定环境，在实际上实施过程中应注意以下事项：<br>
- a. 确认系统所需运行环境及相关资源已准备就绪；
- b. 确保系统运行所需各项配置正确，如数据库连接、网络配置等；
- c. 确保系统能够正常运行。<br>

在实际部署发布过程中由于企业内部实施流程差异，可能需要运维部门支持系统的发布，因此为了系统能够顺利发布，需要与相关人员做好沟通及配合。
### 3.1.2 功能验证
功能验证旨在确保系统上线后各项功能能够正常运行，过程中需要对系统的功能完整性以及系统可靠性进行验证，确保用户能够按照预期进行操作，系统能够在实际使用过程中稳定运行。

由于系统需要与研发流程中所使用工具进行集成，进而实现安全能力的嵌入，因此在测试过程中应重点关注系统与内部所用研发工具是否能够正常集成接入，以及接入后各项操作功能是否正常。

因为系统需要面向所有工程师（包括研发及安全工程师）开放，所以产品的操作文档及知识库的可读性、完整性其实也是挺重要的，需要找几个目标用户对系统配套的文档及操作手册、知识库进行测试验证。

除此之外，对部署的平台进行一轮安全性测试也是非常必要的，以确保安全自身的系统平台的安全性，防止出现安全问题，使得安全团队的专业性遭到质疑。

## 3.2 配套的文档及资源
### 3.2.1 产品安装部署文档
产品安装部署文档的目的是为用户提供系统的详细安装和部署步骤，确保能够顺利将系统部署到指定的环境中，因此在制作产品安装使用文档时应注意以下几点：<br>
- a. 文档应该覆盖系统的所有部署环境，包括物理服务器、虚拟机、云服务等，以满足不同用户的部署需求。
- b. 需要明确列出系统部署所需的硬件和软件环境，包括操作系统版本、数据库版本、依赖库等，确保用户的环境能够满足系统的运行要求。
- c. 按照步骤详细描述系统的安装和配置过程，包括下载安装包、解压文件、配置参数等，确保用户能够按照指导正确完成部署。
- d. 需要提供系统的初始化和启动步骤，包括数据库初始化、服务启动等，确保系统能够顺利启动并进入正常运行状态。

### 3.2.2 操作手册
操作手册旨在为用户提供详细的系统操作指引，保证用户了解及正确使用系统的各项功能，因此提供使用手册时应注意以下几点：<br>
- a. 操作手册需要与系统的实际情况保持一致，确保操作手册中的内容与系统的实际操作一致，避免出现误导用户的情况。
- b. 操作手册的内容应该简明扼要，清晰易懂，避免使用过多的专业术语，确保用户能够快速理解和掌握操作方法。
- c. 操作手册应该按照操作流程和模块划分，对每个步骤进行详细说明，包括文字描述、截图示例等，确保每一步操作清晰明了。

### 3.2.3 产品常见问题解决及故障排除指南
产品常见问题解决及故障排除指南的目的是帮助用户在使用产品时遇到问题时能够快速定位并解决，确保系统的稳定运行，因此在制作产品常见问题解决及故障排除指南应该注意以下几点：
- a. 针对常见问题和故障，提供清晰的解决方法和排查步骤，包括文字说明、截图示例等，让用户能够快速理解和操作。
- b. 根据问题的严重程度和影响范围，将问题分类，区分紧急问题和一般问题，提供相应的解决方案和应对措施。
- c. 需要提供常见问题的预防措施和注意事项，帮助用户避免常见问题的发生，提高系统的稳定性和可靠性。
- d. 在编写指南时，需要考虑用户的技术水平和使用经验，提供简单易懂的解决方案，确保用户能够正确理解和操作。

### 3.2.4 服务支持及质量保障
除了配套的文档及故障解决指南之外，需要提供服务支持群或提供oncall机制作为兜底方案，一方面方便用户反馈一些使用过程中存在的紧急问题，另外一方面也可以从这个群收集用户的使用反馈。建立一个和用户高效沟通的渠道。

既然配备了相应的服务支持群及oncall机制，那么就应该对内对外明确相应的服务质量标准，包括每个问题的响应时效性，问题跟进闭环的保障机制等，同时需要建立对运营人员的考核机制。

此外，需要考虑这一套安全系统出现故障时的降级处置方案，保障不能对业务的正常上线及发布流程造成影响。
