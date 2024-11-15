### 基于自适应边缘智能（Adaptive Edge Intelligence, AEI）和AI实时优化调度的工厂中控系统
#### 什么是边缘计算？
> 边缘计算（Edge Computing）是把计算任务从云端移动到边缘设备上，从而实现在边缘设备上直接计算，从而实现边缘计算。
> 根据《IEEE Transactions on Industrial Informatics》2024年最新发表的研究论文《Edge Computing for Real-Time Data Processing in Smart Manufacturing Systems》（边缘计算在智能制造系统中的实时数据处理），边缘计算通过将计算资源部署在接近数据源的地方，可以显著减少数据传输延迟，提高系统的实时性和可靠性。文章指出，边缘计算在智能制造中的应用主要包括数据预处理、实时监控和局部决策。
#### 什么是人工智能？
> 人工智能（Artificial Intelligence，AI）是指通过计算机算法、模型、程序等非人工 intervention，模拟、复制、学习、模拟人的智能行为，从而实现智能的目标。

#### 什么是自适应边缘智能？（AEI）
> 自适应边缘智能（Adaptive Edge Intelligence, AEI）是边缘计算与人工智能结合的一种技术，它通过在边缘设备上实现智能算法，实现在边缘设备上直接计算，从而实现边缘计算。
> 根据《IEEE Internet of Things Journal》2024年最新发表的研究论文《Adaptive Edge Intelligence for Real-Time Decision Making in Industrial IoT Systems》（自适应边缘智能在工业物联网系统中的实时决策），自适应边缘智能（AEI）是一种新兴的技术，通过在边缘设备上部署自适应的机器学习模型，实现实时数据处理和智能决策。AEI的核心在于模型的自适应性和灵活性，可以根据实时数据动态调整模型参数，提高决策的准确性和效率。
#### 什么是AI实时优化调度？
> AI实时优化调度（AI-based Real-Time Optimization Scheduling, AIRTS）是一种基于人工智能算法的实时调度算法，它通过分析实时数据，实现动态的资源调度，从而实现实时的资源分配和调度。
> 另一篇发表在《Journal of Manufacturing Systems》2024年的论文《Artificial Intelligence for Real-Time Scheduling and Optimization in Manufacturing》（人工智能在制造中的实时调度和优化）中提到，人工智能技术，特别是强化学习和深度学习算法，可以在实时调度中发挥重要作用。这些算法能够根据实时数据动态调整生产计划，优化资源配置，提高生产效率。
#### AEI对于建造智能工厂的中控系统有哪些优势？
> 边缘人工智能够在设备端（如微控制器、传感器等）直接进行数据处理和决策，而不是将数据传输到云端进行处理。
> 相较于传统中控系统中主要依赖于中央服务器进行数据处理和决策，AEI可以减少数据传输延迟，提高响应速度；降低带宽需求，节省网络资源；保护数据隐私，减少数据泄露风险。
#### 如何在嵌入式平台部署边缘人工智能？
#### 如何训练本地大模型？
#### 基于自适应边缘智能（AEI）的工厂中控系统
1. ##### 自适应模型部署：
- **动态模型更新**：在边缘设备上部署自适应的机器学习模型，这些模型可以根据实时数据动态调整参数，提高模型的准确性。
- **模型迁移学习**：利用迁移学习技术，将已有模型的知识迁移到新的任务中，减少模型训练时间和资源消耗。
2. ##### 实时数据处理：
- **低延迟传输**：通过高速网络将预处理后的数据传输到中央中控系统，确保数据传输的低延迟和高可靠性。
- **局部决策**：边缘设备根据自适应模型进行局部决策，例如设备状态监控、故障预警和初步故障处理。
3. ##### 智能优化调度：
- **强化学习算法**：利用强化学习算法，根据实时数据动态调整生产计划，优化生产流程。系统通过不断的试错和学习，逐步提高调度决策的准确性和效率。
- **深度学习模型**：构建深度学习模型，对设备运行状态、生产效率和能耗等多维度数据进行综合分析，预测未来趋势，提供优化建议。
4. ##### 可视化管理平台：
- **实时监控界面**：提供直观的实时监控界面，展示设备的运行状态、生产进度和优化建议。
- **历史数据分析**：支持历史数据的查询和分析，帮助管理人员了解设备的长期运行趋势和优化效果。
- **报告生成工具**：自动生成优化报告和调度建议，方便管理人员进行决策和汇报。

#### 参考资料
[16 认识边缘人工智能(Arduino小型化与TinyML应用——从入门到精通 系列课)](https://www.bilibili.com/video/BV1YXy3YGEDT/?spm_id_from=333.337.search-card.all.click&vd_source=82d6d8197dc1adf463eac4f55a6ee9de)
[两分钟带你了解边缘计算](https://www.bilibili.com/video/BV1Qb411q7FA?spm_id_from=333.788.recommend_more_video.-1&vd_source=82d6d8197dc1adf463eac4f55a6ee9de)
[新手教程 五分钟教你在嵌入式平台部署YOLO](https://www.bilibili.com/video/BV1Qm421g7g1/?spm_id_from=333.337.search-card.all.click&vd_source=82d6d8197dc1adf463eac4f55a6ee9de)