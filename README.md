# SNN_arxiv_daily
this repository records my subscriptions of SNN in arxiv daily, and [these](https://github.com/shenhaibo123/SNN_summaries) are my summaries.

## 2020.11

- **[13]** [Tielin Zhang] Tuning Convolutional Spiking Neural Network with Biologically-plausible Reward Propagation. [paper](https://arxiv.org/abs/2010.04434 "this paper has been uploaded") .

- **[13]** [Zhenzhi Wu] LIAF-Net: Leaky Integrate and Analog Fire Network for Lightweight and Efficient Spatiotemporal Information Processing. [paper](https://arxiv.org/abs/2011.06176 "Spiking neural networks (SNNs) based on Leaky Integrate and Fire (LIF) model
  have been applied to energy-efficient temporal and spatiotemporal processing
  tasks. Thanks to the bio-plausible neuronal dynamics and simplicity, LIF-SNN
  benefits from event-driven processing, however, usually faces the embarrassment
  of reduced performance. This may because in LIF-SNN the neurons transmit
  information via spikes. To address this issue, in this work, we propose a Leaky
  Integrate and Analog Fire (LIAF) neuron model, so that analog values can be
  transmitted among neurons, and a deep network termed as LIAF-Net is built on it
  for efficient spatiotemporal processing. In the temporal domain, LIAF follows
  the traditional LIF dynamics to maintain its temporal processing capability. In
  the spatial domain, LIAF is able to integrate spatial information through
  convolutional integration or fully-connected integration. As a spatiotemporal
  layer, LIAF can also be used with traditional artificial neural network (ANN)
  layers jointly. Experiment results indicate that LIAF-Net achieves comparable
  performance to Gated Recurrent Unit (GRU) and Long short-term memory (LSTM) on
  bAbI Question Answering (QA) tasks, and achieves state-of-the-art performance
  on spatiotemporal Dynamic Vision Sensor (DVS) datasets, including MNIST-DVS,
  CIFAR10-DVS and DVS128 Gesture, with much less number of synaptic weights and
  computational overhead compared with traditional networks built by LSTM, GRU,
  Convolutional LSTM (ConvLSTM) or 3D convolution (Conv3D). Compared with
  traditional LIF-SNN, LIAF-Net also shows dramatic accuracy gain on all these
  experiments. In conclusion, LIAF-Net provides a framework combining the
  advantages of both ANNs and SNNs for lightweight and efficient spatiotemporal
  information processing.   基于泄漏集成和Fire (LIF)模型的尖峰神经网络(Spiking neural networks, SNNs)被应用于时间和时空处理任务中。
  由于生物上似是而非的神经元动力学和简单性，LIF-SNN从事件驱动的处理中获益，然而，通常面临性能下降的尴尬。
  这可能是因为在LIF-SNN中神经元通过尖刺传递信息。
  为了解决这一问题，本文提出了一种漏集模拟Fire (LIAF)神经元模型，使模拟值能够在神经元之间进行传输，并在此基础上构建了一个名为LIAF- net的深度网络，以实现高效的时空处理。
  在时间域，LIAF遵循传统的LIF动力学，保持其时间处理能力。
  在空间领域，LIAF可以通过卷积集成或全连通集成来集成空间信息。
  LIAF作为一种时空层，也可以与传统的人工神经网络(ANN)层联合使用。
  实验结果表明LIAF-Net达到类似性能的复发性单元(格勒乌)和长期短期记忆(LSTM)泛神教义问答(QA)的任务,并达到最先进的性能时空动态视觉传感器(dv)的数据集,包括MNIST-DVS CIFAR10-DVS DVS128姿态,更少数量的突触权重和计算开销与传统网络相比由LSTM,格勒乌,
  卷积LSTM (ConvLSTM)或3D卷积(Conv3D)。
  与传统的LIF-SNN相比，LIAF-Net在所有实验中都有显著的精度提高。
  综上所述，LIAF-Net提供了一个框架，结合了ann和SNNs的优点，实现了轻量级和高效的时空信息处理。[[") .

- **[11]** [Hanle Zheng] Going Deeper With Directly-Trained Larger Spiking Neural Networks. [paper](https://arxiv.org/abs/2011.05280 "Spiking neural networks (SNNs) are promising in a bio-plausible coding for
  spatio-temporal information and event-driven signal processing, which is very
  suited for energy-efficient implementation in neuromorphic hardware. However,
  the unique working mode of SNNs makes them more difficult to train than
  traditional networks. Currently, there are two main routes to explore the
  training of deep SNNs with high performance. The first is to convert a
  pre-trained ANN model to its SNN version, which usually requires a long coding
  window for convergence and cannot exploit the spatio-temporal features during
  training for solving temporal tasks. The other is to directly train SNNs in the
  spatio-temporal domain. But due to the binary spike activity of the firing
  function and the problem of gradient vanishing or explosion, current methods
  are restricted to shallow architectures and thereby difficult in harnessing
  large-scale datasets (e.g. ImageNet). To this end, we propose a
  threshold-dependent batch normalization (tdBN) method based on the emerging
  spatio-temporal backpropagation, termed "STBP-tdBN", enabling direct training
  of a very deep SNN and the efficient implementation of its inference on
  neuromorphic hardware. With the proposed method and elaborated shortcut
  connection, we significantly extend directly-trained SNNs from a shallow
  structure ( < 10 layer) to a very deep structure (50 layers). Furthermore, we
  theoretically analyze the effectiveness of our method based on "Block Dynamical
  Isometry" theory. Finally, we report superior accuracy results including 93.15
  % on CIFAR-10, 67.8 % on DVS-CIFAR10, and 67.05% on ImageNet with very few
  timesteps. To our best knowledge, it's the first time to explore the
  directly-trained deep SNNs with high performance on ImageNet   尖峰神经网络(SNNs)在时空信息和事件驱动信号处理的生物编码方面很有前途，非常适合在神经形态硬件中实现高能效。
  然而，SNNs独特的工作模式使其比传统网络更难培养。
  目前，探索高性能深度SNNs的训练主要有两条路径。
  第一种是将预先训练好的神经网络模型转换为SNN模型，该模型通常需要较长的编码窗口来收敛，在训练时无法利用时空特征来求解时间任务。
  二是在时空域直接训练SNNs。
  但由于激发函数的二元脉冲活动和梯度消失或爆炸问题，目前的方法仅限于浅层架构，因此难以利用大规模数据集(如ImageNet)。
  为此，我们提出了一种基于新兴时空反向传播的阈值相关批归一化(tdBN)方法，称为"STBP-tdBN"，能够直接训练深度SNN，并有效地在神经形态硬件上实现其推理。
  通过所提出的方法和详细的快捷连接，我们显著地将直接训练的SNNs从浅层结构(&lt;
  10层)到非常深的结构(50层)。
  基于块体动态等距理论，从理论上分析了该方法的有效性。
  最后，我们报告了在很少时间步长的情况下，CIFAR-10的准确率为93.15%，ds - cifar10的准确率为67.8%，ImageNet的准确率为67.05%。
  据我们所知，这是首次在ImageNet上探索直接训练的高性能深度SNNs[[") .

-  [10] [Bruno Golosio] Fast simulations of highly-connected spiking cortical models using GPUs. [paper](https://arxiv.org/abs/2007.14236 "this paper has been uploaded") .

-  [10] [Srivatsa P] You Only Spike Once: Improving Energy-Efficient Neuromorphic Inference to ANN-Level Accuracy. [paper](https://arxiv.org/abs/2006.09982 "this paper has been uploaded.") .

- [10] [Yahui Zhang] All-optical neuromorphic binary convolution with a spiking VCSEL neuron for image gradient magnitudes. [paper](https://arxiv.org/abs/2011.04438 "All-optical binary convolution with a photonic spiking vertical-cavity
  surface-emitting laser (VCSEL) neuron is proposed and demonstrated
  experimentally for the first time. Optical inputs, extracted from digital
  images and temporally encoded using rectangular pulses, are injected in the
  VCSEL neuron which delivers the convolution result in the number of fast (<100
  ps long) spikes fired. Experimental and numerical results show that binary
  convolution is achieved successfully with a single spiking VCSEL neuron and
  that all-optical binary convolution can be used to calculate image gradient
  magnitudes to detect edge features and separate vertical and horizontal
  components in source images. We also show that this all-optical spiking binary
  convolution system is robust to noise and can operate with high-resolution
  images. Additionally, the proposed system offers important advantages such as
  ultrafast speed, high energy efficiency and simple hardware implementation,
  highlighting the potentials of spiking photonic VCSEL neurons for high-speed
  neuromorphic image processing systems and future photonic spiking convolutional
  neural networks.  首次提出并实验证明了与光子尖顶垂直腔面发射激光(VCSEL)神经元的全光二元卷积。
  从数字图像中提取并使用矩形脉冲进行时间编码的光学输入被注入到VCSEL神经元中，该神经元以快速(100ps长)脉冲发射的次数传递卷积结果。
  实验和数值结果表明，单spiking VCSEL神经元可以成功地实现二值卷积，全光二值卷积可以用于计算图像梯度大小，用于检测边缘特征和分离源图像的垂直分量和水平分量。
  我们还证明了这个全光尖峰二进制卷积系统对噪声具有很好的鲁棒性，并且可以处理高分辨率的图像。
  此外，该系统具有速度快、能量效率高和硬件实现简单等重要优点，突出了尖形光子VCSEL神经元在高速神经形态图像处理系统和未来光子尖形卷积神经网络中的潜力[[") .

- **[5]** [Malu Zhang] Rectified Linear Postsynaptic Potential Function for Backpropagation in Deep Spiking Neural Networks. [paper](https://arxiv.org/abs/2003.11837 "脉冲神经网络(SNNs)利用时空脉冲模式来表示和传输信息，不仅具有生物学上的真实性，而且适用于超低功耗事件驱动的神经形态实现。
  在深度学习成功的激励下，深度尖峰神经网络(DeepSNNs)的研究为人工智能应用提供了前景广阔的方向。
  然而，DeepSNNs的训练并不简单，因为研究充分的误差反向传播(BP)算法并不直接适用。
  在本文中，我们首先建立了一个理解，为什么误差反向传播不能很好地工作在深度snns。
  为了解决这个问题，我们提出了一种简单而有效的直线型突触后电位函数(ReL-PSP)用于尖峰神经元，并提出了一种依赖于尖峰时间的反向传播(STDBP)学习算法用于深度神经网络。
  在STDBP算法中，利用单个峰值的时间来传递信息(时间编码)，并以事件驱动的方式基于峰值的时间进行学习(反向传播)。
  实验结果表明，该学习算法在基于单峰值时间的深度神经网络学习算法中取得了较高的分类精度。
  此外，利用从STDBP学习算法获得的训练模型参数，我们演示了在最近提出的神经形态推断加速器上的超低功率推理操作。
  实验结果表明，neuromorphic硬件消耗总功耗为0.751~mW，实现了47.71~ms的低延迟从MNIST数据集图像分类。
  总的来说，这项工作研究了脉冲时序动力学对信息编码、突触可塑性和决策的贡献，为未来的深度神经网络和神经形态硬件系统的设计提供了一个新的视角。[") .

- [3] [Fabio Schittler Neves] Controlled Perturbation-Induced Switching in Pulse-Coupled Oscillator Networks. [paper](https://arxiv.org/abs/2011.00888 "脉冲耦合系统，如尖峰神经网络，显示非平凡不变量集的形式吸引，但不稳定鞍状周期轨道，单位同步成组。
  这些轨道之间的异宿连接在原则上可能支持这些网络中的交换过程，并使新型的神经计算成为可能。
  对于小型的耦合振荡器网络，我们在这里研究在什么条件下以及系统的对称性如何加强或禁止某些可能由扰动引起的开关跃迁。
  对于五振子网络，我们推导出两簇对称与连续耦合的振子对称的显式转移规则。
  第三种对称产生了由具有这种对称的不稳定吸引子集合和它们之间的连接组成的异诊所网络。
  我们的结果表明，脉冲耦合系统可以可靠地产生定义良好的复杂时空模式集，符合特定的跃迁规则。
  我们简要讨论尖峰神经系统的计算可能的含义。[") .

- [3] [Julien Dupeyroux] Neuromorphic control for optic-flow-based landings of MAVs using the Loihi processor [paper](https://arxiv.org/abs/2011.00534 "像Loihi这样的神经形态处理器提供了一种很有前途的传统计算模块的替代品，可以为受约束的系统，如微型飞行器(MAVs)，提供健壮、高效和自主的技能，如起飞和着陆、避障和追踪。
  然而，在机器人平台上使用这种处理器的一个主要挑战是仿真和真实世界之间的现实差距。
  在本研究中，我们首次提出Loihi神经形态芯片原型在飞行机器人上的完全嵌入式应用。
  在此基础上，提出了一种基于腹侧光流场发散度的脉冲神经网络来计算推力指令，实现了自主着陆。
  进化是在使用PySNN库的基于python的模拟器中执行的。
  最终的网络结构只有35个神经元分布在3层中。
  仿真与Loihi的定量分析表明，推力设定值的均方根误差低至0.005 g，隐含层的脉冲序列匹配率为99.8%，输出层的匹配率为99.7%。
  所提出的方法成功地弥合了现实差距，为未来机器人神经形态的应用提供了重要的见解。[") , [Supplementary material](https://mavlab.tudelft.nl/loihi/.) .

- [3] [ Joshua Mack] RANC: Reconfigurable Architecture for Neuromorphic Computing.  [paper](https://arxiv.org/abs/2011.00624 "神经形态结构已被引入作为高效尖突神经网络执行的平台。
  这些架构所提供的大量并行性也引发了非机器学习应用领域的兴趣。
  为了为硬件设计者和应用开发者打开进入的障碍，我们提出了RANC:一个神经形态计算的可重构架构，一个开源的高度灵活的生态系统，它能够在软件上通过c++仿真和硬件上通过FPGA仿真进行神经形态架构的快速实验。
  我们展示了RANC生态系统的效用，展示了它重建IBM TrueNorth行为的能力，并与IBM的Compass模拟环境和出版的文献进行了直接比较。
  RANC允许基于应用洞见优化架构，也可以原型化未来的神经形态架构，以完全支持新的应用类别。
  我们通过基于肺泡U250 FPGA进行定量分析，研究架构变化对提高应用程序映射效率的影响，展示了RANC的高度参数化和可配置性。
  我们提供了跨实现合成孔径雷达分类和向量矩阵乘法应用的后路由资源使用和吞吐量分析，并演示了可伸缩到模拟259K不同神经元和73.3M不同突触的神经形态体系结构。[ ") , [source code](https://github.com/UA-RCL/RANC) .

  

**the following subscribes came from my  senior: [LuoYiHao](https://github.com/luoyihao666). and I will sort them out two weeks later.

## 2020.10

- [ ] ### Going Deeper With Directly-Trained Larger Spiking Neural Networks

  ​		尖峰神经网络（SNN）在时空信息和事件驱动的信号处理的生物合理编码中很有前途，这非常适合在神经形态硬件中高效实现。但是，SNN的独特工作模式使它们比传统网络更难以训练。当前，有两条主要途径探索具有高性能的深度SNN的训练。首先是将经过预训练的ANN模型转换为其SNN版本，这通常需要较长的编码窗口才能收敛，并且在训练中无法利用时空特征来解决时态任务。另一种是在时空域中直接训练SNN。但是由于触发函数的二进制尖峰活动以及梯度消失或爆炸的问题，当前的方法仅限于浅层架构，因此难以利用大规模数据集（例如ImageNet）。为此，我们提出了一种基于新兴时空反向传播的阈值相关批归一化（tdBN）方法，称为“ STBP-tdBN”，它可以直接训练非常深的SNN并有效地实现对神经形态硬件的推断。通过提出的方法和精心设计的快捷连接，我们将直接训练的SNN从浅结构（<10层）显着扩展到了非常深的结构（50层）。此外，我们从理论上分析了基于“块动态等距”理论的方法的有效性。最后，我们报告了极高的准确性结果，包括CIFAR-10的93.15％，DVS-CIFAR10的67.8％和ImageNet的67.05％，而这些步骤几乎不需要时间。据我们所知，这是第一次在ImageNet上探索具有高性能的直接训练的深度SNN



### Strategy and Benchmark for Converting Deep Q-Networks to Event-Driven Spiking Neural Networks

尖峰神经网络（SNNs）在专用神经形态硬件上实现深度神经网络（DNNs）具有巨大的潜力。最近的研究表明，SNNs在图像分类任务（包括CIFAR-10和ImageNet数据）上与DNNs相比具有竞争性。目前的工作集中于在ATARI游戏中结合使用snn和深度强化学习，这涉及到比图像分类更多的复杂性。我们回顾了将DNNs转换为snn的理论，并将其扩展到深Q网络（DQNs）。为了减少转换过程中的误差，我们提出了一种鲁棒的发射率表示方法。此外，我们引入了一种新的度量方法，通过比较DQN和SNN的决策来评估转换过程。分析了仿真时间和参数归一化对转换后snn性能的影响。我们在17场表现最好的阿塔里游戏中取得了竞争性的分数。据我们所知，我们的工作是第一个在多个带有snn的Atari游戏上实现最先进性能的工作。我们的工作为DQNs到SNNs的转换提供了一个基准，为进一步研究用SNNs解决强化学习任务铺平了道路

 

### Revisiting Batch Normalization for Training Low-latency Deep Spiking Neural Networks from Scratch

由于稀疏，异步和二进制事件（或尖峰）驱动的处理，尖峰神经网络（SNN）最近已成为深度学习的替代方法，它可以为神经形态硬件带来巨大的能源效率收益。大多数现有的创建SNN的方法要么转换预训练的人工神经网络（ANN）的权重，要么直接使用替代梯度反向传播训练SNN。每种方法都有其优点和缺点。从ANN到SNN的转换方法至少需要数百个时间步才能进行推断，以产生具有竞争力的准确性，进而降低了节能量。从头开始使用替代梯度训练SNN可以减少等待时间或总时间步数，但是训练变得缓慢/有问题，并且存在收敛问题。因此，后一种训练SNN的方法仅限于简单数据集上的浅层网络。为了解决SNN中的训练问题，我们重新审视了批次标准化，并提出了一种基于时间的时间批次标准化（BNTT）技术。到现在为止，大多数以前的SNN工作都忽略了批量归一化，因为它对训练时间SNN无效。与以前的工作不同，我们提出的BNTT将BNTT层中的参数沿时间轴解耦，以捕获峰值的时间动态。 BNTT中随时间变化的可学习参数允许神经元通过不同的时间步长控制其尖峰速率，从而实现从头开始的低延迟和低能量训练。我们对CIFAR-10，CIFAR-100，Tiny-ImageNet和事件驱动的DVS-CIFAR10数据集进行了实验。 BNTT允许我们以很少的25-30个时间步长，从头开始在复杂的数据集上训练深度SNN架构。我们还提出了一种提前退出算法，该算法使用BNTT中的参数分布来减少推理时的等待时间，从而进一步提高了能源效率

 

### DCT-SNN: Using DCT to Distribute Spatial Information over Time for Learning Low-Latency Spiking Neural Networks

尖峰神经网络（SNN）提供了一种有希望的替代传统深度学习框架的方法，因为由于事件驱动的信息处理，它们提供了更高的计算效率。 SNN将像素强度的模拟值随时间分布为二进制峰值。但是，最广泛使用的输入编码方案（例如基于泊松的速率编码）无法有效利用SNN的附加时间学习能力。此外，这些SNN具有较高的推理延迟，这是其部署的主要瓶颈。为克服此问题，我们提出了一种基于时间的可伸缩编码方案，该方案利用离散余弦变换（DCT）来减少推理所需的时间步数。 DCT将图像分解为正弦基准图像的加权和。在每个时间步长，将DCT系数和单个频率基的Hadamard乘积按顺序提供给累加器，该累加器在超过阈值时会产生尖峰。我们使用拟议的方案来学习DCT-SNN，这是一种具有时滞积分和发射神经元的低延迟深度SNN，并使用基于替代梯度下降的反向传播技术进行了训练。使用VGG架构，我们在CIFAR-10，CIFAR-100和TinyImageNet上的top-1准确性分别达到89.94％，68.3％和52.43％。值得注意的是，与其他最新的SNN相比，DCT-SNN的推理延迟减少了2-14倍，同时达到了与标准深度学习同行相当的准确性。变换的维数使我们可以控制推理所需的时间步数。此外，我们可以通过在推理过程中降低最高频率分量，以原则上的方式在准确性与延迟之间进行权衡

 

### Finite Meta-Dynamic Neurons in Spiking Neural Networks for Spatio-temporal Learning

 

尖刺神经网络（SNN）融合了生物学上似乎更合理的结构和学习原理，因此在弥合人工神经网络与自然神经网络之间的差距方面发挥着关键作用。尖峰信号是稀疏信号，描述了基于阈值的事件触发和膜电位的阈值下动态计算，这为我们提供了一种替代的统一且有效的信息表示和计算方式。受生物网络的启发，在该网络中，有限数量的元神经元集成在一起以实现各种认知功能，我们提出并构建了元动态神经元（MDN），以改进SNN，以便在时空学习中更好地进行网络泛化。 MDN设计时具有基本的神经元动力学，其中包含膜电位的一阶和二阶动力学，包括某些超参数支持的时空元类型。首先从空间（MNIST）和时间（TIDigits）数据集生成MDN，然后将其扩展到其他各种不同的时空任务（包括Fashion-MNIST，NETtalk，Cifar-10，TIMIT和N-MNIST）。与其他SOTA SNN算法相比，达到了可比较的精度，并且使用MDN的SNN与不使用MDN的SNN相比，也获得了更好的概括

### Connection Pruning for Deep Spiking Neural Networks with On-Chip Learning

较长的培训时间阻碍了在嵌入式系统硬件上实现具有在线学习功能的深度Spiking神经网络（SNN）的潜力。我们的工作提出了一种新颖的连接修剪方法，该方法可在基于基于Spike Timing时序可塑性（STDP）的在线学习中应用，以优化学习时间和SNN的网络连接性。我们的连接修剪方法已在具有初次尖峰时间（TTFS）编码的深度SNN上进行了评估，并已成功实现在线学习中2.1倍的加速，并减少了92.83％的网络连接。在线学习中的能耗节省了64％。此外，连通性降低导致推理速度提高2.83倍，并节省了78.24％的能量。同时，分类精度与Caltech 101数据集上的非修剪基准保持相同。此外，我们在现场可编程门阵列（FPGA）平台上开发了事件驱动的硬件体系结构，该体系结构有效地结合了我们提出的连接修剪方法，而产生的功率开销仅为0.56％。此外，我们在工作和现有SNN连接修剪的工作之间进行了比较，以突出每种方法的关键特征。据我们所知，我们的工作是第一个提出连接修剪算法的方法，该算法可用于基于TTFS编码的基于深度STNN的在线基于STDP的学习中

 

### Tuning Convolutional Spiking Neural Network with Biologically-plausible Reward Propagation

与标准的人工神经网络（ANN）相比，尖刺神经网络（SNN）包含更多的生物学现实结构和生物学启发的学习原理。 SNN中的动态神经元是非差分的，包含衰减的历史状态并在其状态达到触发阈值后生成基于事件的尖峰。 SNN的这种动态特性使其很难直接用标准反向传播（BP）进行训练，而标准反向传播被认为在生物学上是不可行的。本文提出了一种生物合理的奖励传播（BRP）算法，并将其应用于具有尖峰卷积（具有1D和2D卷积核）和全连接层的SNN架构。与将错误信号从错误信号逐层传播到突触前神经元的标准BP不同，BRP将目标标记而不是目标错误直接从输出层传播到所有预隐层。这种努力与新皮质皮层中自上而下的奖励指导学习更加一致。然后，使用伪BP诱导仅具有局部梯度差异的突触修饰，也可将其替换为穗定时依赖性可塑性（STDP）。提议的BRP-SNN的性能在空间（包括MNIST和Cifar-10）和时间（包括TIDigits和DvsGesture）任务上得到了进一步验证。实验结果表明，BRP在SNN的融合学习中发挥了作用，与其他最新的SNN算法相比，其准确性更高，并且与ANN相比，节省了50％以上的计算成本。我们认为在生物学上逼真的SNN的训练过程中引入生物学上可行的学习规则可能会给我们带来更多的提示和启发，以更好地理解生物学系统的智能性

 

### Analogical and Relational Reasoning with Spiking Neural Networks

瑞文的递进矩阵被广泛用于测量人类的抽象推理和智力。然而对于人工学习系统来说，抽象推理仍然是一个具有挑战性的问题。在这篇论文中，我们研究了神经网络如何在解决这个问题上获得显著的优势。为了说明这一点，我们首先研究了有监督学习的网络性能，然后研究了无监督学习网络的性能。在RAVEN数据集上的实验表明，我们的有监督网络的整体精度超过了人类水平的性能，而我们的无监督网络显著优于现有的无监督方法。最后，我们的有监督学习和无监督学习的结果表明，与非增广学习不同，具有尖峰模块的网络能够在没有任何明确指令的情况下提取和编码时间特征，不依赖训练数据，并且更容易推广到新问题。综上所述，本文报告的结果表明，具有尖峰模块的人工神经网络非常适合解决抽象推理问题

 

### EqSpike: Spike-driven Equilibrium Propagation for Neuromorphic Implementations

神经形态系统通过以大脑启发的方式，利用尖峰运算实现高能量效率。然而，寻找能够在神经形态系统的局部约束下实现的基于尖峰的学习算法，在获得高精度的同时，仍然是一个巨大的挑战。平衡传播是一种硬件友好的反向传播方法，只涉及空间局部计算，适用于具有静态输入的递归神经网络。到目前为止，面向硬件的均衡传播研究主要集中在基于速率的网络上。在这项工作中，我们开发了一种称为EqSpike的尖峰神经网络算法，它与神经形态系统兼容，通过平衡传播进行学习。通过仿真，我们在MNIST上获得了96.9%的测试识别准确率，与基于速率的均衡传播相似，并与用于峰值神经网络的其他学习技术进行了比较。我们证明，与gpu相比，在硅神经形态技术中实现的EqSpike可以将推理和训练的能耗降低三个数量级。最后，我们还表明，在学习过程中，EqSpike权重更新表现出一种尖峰时间依赖的可塑性，突出了与生物学的可能联系

 

### Quantum Superposition Spiking Neural Network

量子脑作为一种新的假设，指出量子计算中的一些非平凡机制，例如叠加和纠缠，可能对脑功能的形成具有重要影响。受此想法的启发，我们提出了量子叠加加标神经网络（QS-SNN），该技术将量子叠加引入尖峰神经网络模型，以应对其他先进的机器学习模型难以应对的挑战。对于人脑而言，无论背景如何变化，都必须掌握主要信息，才能有效地与各种环境交互。例如，无论是黑色背景的白色字符还是白色背景的反向黑色字符，人类都容易识别数字。虽然如果当前的机器学习模型是用其中一种情况（例如带有黑色背景的白色字符）进行训练的，则几乎不可能让他们识别出颜色反转的版本。为了应对这一挑战，我们提出了一种具有重叠状态编码的两格尖峰神经网络，该网络受量子信息理论和大脑中神经元信息编码的时空尖峰特性的启发。完全连接的ANN，VGG，ResNet和DenseNet之类的典型网络结构面临相同任务的挑战。我们在原始图像数据集上训练这些网络，然后反转背景色以测试其概括。结果表明，本文提出的量子叠加加标神经网络（QS-SNN）能够成功地识别彩色逆像，而人工神经网络无法应对这种情况。此外，当在输入上添加噪声时，QS-SNN表现出其鲁棒性

 

### Lamina-specific neuronal properties promote robust, stable signal propagation in feedforward networks

前馈网络（FFN）是神经系统中无处不在的结构，已经进行了研究以了解可靠的信号和信息传输机制。在许多FFN中，一层神经元具有与突触前/突触后层不同的内在属性，但是如何影响网络级信息处理尚待探索。在这里，我们显示了由层状特定细胞特性引起的层到层异质性促进了FFN中的信号和信息传输。具体来说，我们发现，由输入驱动的尖峰信号上的神经元的每一层进行的信号变换，可以解调由前一层引入的信号失真。此机制可增强传播的尖峰信号所携带的信息传输，从而支持深度FFN中可靠的尖峰信号和信息传输。我们的研究表明，神经回路中不同的细胞类型执行不同的计算功能，总体上有助于信息处理

### Optimized spiking neurons can classify images with high accuracy through temporal coding with two spikes

 

基于Spike的神经形态硬件是减少图像分类和其他深度学习应用程序能耗的有前途的选择。为了在手机或其他边缘设备中实现深度学习的最新结果，尤其需要大幅度降低能耗。但是，直接训练深度尖峰神经网络很困难，并且以前的将训练后的人工神经网络转换为尖峰神经元的方法效率低下，因为神经元必须发出太多尖峰。我们显示出，当为此目的优化尖峰神经元模型时，会出现实质上更有效的转换，因此，对于信息传输而言，神经元发出多少尖峰不仅重要，而且信息发出时也很重要。这提高了使用尖峰神经元进行图像分类所能达到的精度，并且所得的网络平均每个神经元仅需要两个尖峰即可对图像进行分类。此外，我们的新转换方法大大提高了生成的尖峰网络的延迟和吞吐量

### Skip-Connected Self-Recurrent Spiking Neural Networks with Joint Intrinsic Parameter and Synaptic Weight Training

作为尖峰神经网络（SNN）的重要一类，递归尖峰神经网络（RSNN）具有强大的计算能力，已被广泛用于处理音频和文本等顺序数据。但是，大多数RSNN都有两个问题。 1.由于缺乏架构指导，经常采用随机循环连接，这不能保证良好的性能。 2.对RSNN的训练通常具有挑战性，瓶颈是可达到的模型准确性。为了解决这些问题，我们提出了一种新型的RSNN，称为跳过连接的自循环SNN（ScSr-SNN）。 ScSr-SNN中的递归是通过将自循环连接添加到尖峰神经元上来以定型方式引入的，从而实现了局部记忆。不相邻层之间的跳过连接丰富了网络动态。通过简化的自循环和跳过连接构建，ScSr-SNN能够实现类似于更复杂的RSNN的循环行为，而由于网络的前馈特性，可以更直接地计算误差梯度。此外，我们提出了一种新的反向传播（BP）方法，称为反向传播内在可塑性（BIP），以通过训练内在模型参数进一步提高ScSr-SNN的性能。与根据神经元活动调整神经元内在参数的标准内在可塑性规则不同，除突触权重训练外，所提出的BIP方法还基于明确定义的全局损失函数的反向传播误差梯度来优化内在参数。基于具有挑战性的语音和神经形态语音数据集（包括TI46-Alpha，TI46-Digits和N-TIDIGITS），与通过最新技术训练的其他类型的RSNN相比，拟议的ScSr-SNN可以将性能提高多达2.55％。 BP方法

### The Heidelberg spiking datasets for the systematic evaluation of spiking neural networks

 

尖峰神经网络是大脑中多功能且节能的信息处理的基础。尽管我们目前对这些网络的计算方式缺乏详细的了解，但是最近开发的优化技术使我们能够在计算机上实例化日益复杂的功能突跳神经网络。这些方法有望构建更有效的非冯-诺依曼计算硬件，并为寻求解开脑电路功能提供新的前景。为了加快此类方法的开发，比较它们的性能的客观方法是必不可少的。但是，目前，还没有广泛接受的用于比较尖峰神经网络的计算性能的方法。为了解决这个问题，我们引入了两个基于峰值的分类数据集，广泛适用于对尖峰神经网络的软件和神经形态硬件实现进行基准测试。为实现此目的，我们开发了一种受神经生理学启发的通用音频转加标转换程序。此外，我们将此转换应用于现有的和新颖的语音数据集。后者是我们专门为此研究创建的免费，高保真度和单词级对齐的海德堡数字数据集。通过训练一系列常规分类器和峰值分类器，我们显示出利用这些数据集中的尖峰定时信息对于良好的分类精度至关重要。这些结果可作为尖峰神经网络未来性能比较的第一参考

 

### Spiking Neural Networks -- Part I: Detecting Spatial Patterns

（SNN）是受生物学启发的机器学习模型，它建立在动态神经元模型的基础上，以事件驱动，在线方式处理二进制和稀疏尖峰信号。 SNN可以在神经形态计算平台上实现，而神经形态计算平台是用于学习和推理的高能效协处理器。 这是三篇论文的系列文章中的第一篇，该论文通过重点介绍模型，算法和应用程序，向工程师群体介绍了SNN。 在第一篇论文中，我们首先介绍了用于常规人工神经网络（ANN）和SNN的神经模型。 然后，我们回顾了SNN的学习算法和应用，这些算法旨在通过检测或生成速率编码尖峰信号中的空间模式来模仿ANN的功能。 我们专门讨论ANN到SNN的转换和神经采样。 最后，我们通过实验验证了SNN的检测和生成空间模式的能力

 

### Spiking Neural Networks -- Part II: Detecting Spatio-Temporal Patterns

受生物大脑操作的启发，尖峰神经网络（SNN）具有独特的能力来检测以尖峰信号的时空模式编码的信息。需要时空处理的数据类型的例子包括时间戳的日志，例如推文的日志，以及神经假体和神经形态传感器的输出。在本文中，这是有关SNN的三篇系列文章中的第二篇，我们首先针对主导方法的模型和训练算法进行审查，该方法和方法将SNN视为递归神经网络（RNN），并根据时间的反向传播调整学习规则以适应需求的SNN。为了解决尖峰机制的不可微性，最新技术的解决方案使用替代梯度来替代具有可微函数的阈值激活函数。然后，我们描述了一种替代方法，该方法依赖于概率模型来加标神经元，从而允许通过梯度的随机估计来推导局部学习规则。最后，提供了针对神经形态数据集的实验，从而在不同SNN模型下获得了关于准确性和收敛性的见解

### Spiking Neural Networks -- Part III: Neuromorphic Communications

无线通信与人工智能之间的协同作用正日益激发着这两个领域的交集。一方面，越来越多的无线连接设备（每个设备都有自己的数据）的存在推动着从高性能计算设备中导出机器学习（ML）进步的努力，这些设备在单个位置存储和处理信息，在最终用户处进行分布式，注重隐私的处理。另一方面，机器学习可以解决通信协议优化中的算法和模型缺陷。但是，在通过带宽受限的通道连接的电池供电设备上实现用于学习和推理的ML模型仍然具有挑战性。本文探讨了尖峰神经网络（SNN）可以帮助解决这些开放问题的两种方法。首先，我们讨论用于SNN分布式训练的联合学习，然后描述神经形态感应，SNN和脉冲无线电技术的集成，以实现低功耗远程推理

 

### Ensembles of Spiking Neural Networks

本文证明了可以构建尖峰神经网络的集成体，从而保证整体性能优于单个模型的平均性能。尖刺神经网络并没有挑战传统神经网络在相同问题上获得的性能。集成学习是已广泛用于改善机器学习模型性能的框架。在本文中，我们展示了如何构建尖峰神经网络的集合，这些集合既可以产生最新的结果，又可以使用原始模型的不到50％的参数来实现。我们建立了结合模型预测的方法论，从而保证了尖峰乐团的性能改进。为此，我们将尖峰神经网络形式化为GLM预测变量，从而为其目标域确定合适的表示形式。此外，我们展示了如何使用歧义分解来测量尖峰合奏的多样性



## 2020.9

### A Deep 2-Dimensional Dynamical Spiking Neuronal Network for Temporal Encoding trained with STDP

众所周知，大脑是高度复杂的异步动态系统，高度适合于对时间信息进行编码。但是，最近的深度学习方法并未利用这种时间编码。尖刺神经网络（SNN）可以使用生物学上逼真的学习机制进行训练，并且可以具有与生物学相关的神经元激活规则。这种类型的网络还从根本上构造为通过时间衰减电压更新来接收时间信息，这是当前速率编码网络难以处理的一种输入。在这里，我们表明，具有动态，混沌活动的大型深层SNN能够模仿具有生物启发性学习规则（例如STDP）的哺乳动物皮质，能够编码来自时态数据的信息。我们认为，网络权重固有的随机性使神经元可以形成组，该组对使用STDP自组织后输入的时间数据进行编码。我们旨在证明输入刺激的精确定时对于在分层网络中形成同步神经组至关重要。我们根据网络熵作为信息传递的度量标准来分析网络。我们希望立即解决两个问题：创建用于人工智能的人工时态神经系统，以及解决大脑中的编码机制

 

### On the Self-Repair Role of Astrocytes in STDP Enabled Unsupervised SNNs

神经形态计算最近已成为一种破坏性的计算范例，它试图在下一代机器学习平台的算法和硬件设计中模拟大脑的基础结构和功能的各个方面。 这项工作超出了当前神经形态计算体系结构在神经元和突触计算模型上的关注范围，以检查可能有助于认知尤其是自我修复的生物大脑的其他计算单元。 我们从计算神经科学中汲取关于胶质细胞功能的灵感和见解，并探索它们在使用钉时标相关可塑性（STDP）的无监督方式训练的尖峰神经网络（SNN）的容错能力中的作用。 我们描述了可以在此类网络中启用的自我修复的程度，故障程度从50％到90％不等，并评估了我们在MNIST和Fashion-MNIST数据集上的建议

 

### Short-term synaptic plasticity optimally models continuous environments

由于诸如基于尖峰的通信和局部活动驱动的突触可塑性等特性，生物神经网络以非凡的能源效率运行。 在计算机模拟时，这些属性还可以实现高能效的机器学习和推理系统。 但是，目前尚不清楚这些机制是否仅权衡了性能与效率之间的关系，还是对生物智能的优越性负有部分责任。 在这里，我们首先从理论上解决这个问题，严格地证明，随机但连续变化的环境（一种常见的自然环境）的最佳预测和推断确实依赖于通过短期尖峰时序相关可塑性（生物神经网络的标志）的适应性。 其次，我们通过仿真评估了这一理论上的最优性，并展示了改进的人工智能（AI）。 在识别通过移动遮挡转换的视频帧的示例任务中，首次在很大程度上由生物学建模的尖峰神经网络（SNN）超越了最新的人工神经网络（ANN）。 与经过深度学习训练的人工神经网络相比，即使在很少，静止且未转换的图像上进行训练，SNN也可以更准确地识别帧，并且具有无监督和突触局部学习，二进制峰值和单层神经元。 这些结果表明，在线适应性和基于峰值的计算可以优化自然环境的自然智能。 此外，这将开发AI的生物神经突触特性的目标从单纯的效率扩展到了计算的绝对优势

### EventProp: Backpropagation for Exact Gradients in Spiking Neural Networks

我们推导了用于传播神经网络的反向传播算法，该神经网络由连续运行的泄漏积分和发射神经元组成。该算法EventProp通过反向传播时间误差来计算尖峰时间和膜电位的任意损失函数的精确梯度。第一次，通过利用最佳控制理论中的方法，我们能够通过尖峰不连续性来反向传播误差，并避免近似或平滑操作。 EventProp可以应用于具有任意连接性的尖峰网络，包括循环，卷积和深度前馈体系结构。虽然我们在这项工作中考虑了泄漏的集成并发射神经元模型，但我们得出梯度的方法可以应用于其他尖峰神经元模型。由于错误是以基于事件的方式（在峰值时间）反向传播的，因此EventProp仅在这些时间要求存储状态变量，从而提供了良好的内存要求。我们演示了如何使用基于事件的模拟器和使用尖峰时间延迟编码的非线性可分离数据集在深峰网络中通过EventProp计算的梯度进行学习。我们的工作支持对基于梯度的方法的严格研究，以训练尖峰神经网络，同时提供对神经形态硬件中学习算法发展的见解

 

## 2020.7~8

### Spiking Associative Memory for Spatio-Temporal Patterns

尖峰时序相关可塑性是一种学习形式，已在真实的皮质组织中得到证明，但是尝试将其用于人造系统并没有取得良好的效果。本文力图通过两个重大进展来对此进行补救。首先是开发一种简单的称为循环STDP的随机学习规则，该规则可以提取以一组神经元的精确尖峰时间编码的模式。我们表明，具有这种学习规则的神经元群体可以充当有效的短期联想记忆，在延长的时间段内存储并可靠地调用大量模式关联。第二个主要主题探讨了与训练神经元在精确的时间产生尖峰相关的挑战，以及在进一步学习发生时要保持尖峰召回时间的保真度。学习规则要求使用精确定时的尖峰信号进行强约束（所谓的时间编码），但也与人们认为使用这样的编码方案以使尖峰神经网络成为灵活智能的竞争解决方案的必要性相一致。持续学习环境中的系统。编码和学习规则在单层关联记忆（由3,200个完全连接到相似大小的记忆神经元群的连接神经元组成的输入层）的设计中得到了证明，我们对此进行了模拟和表征。探索设计注意事项和澄清在设计师控制下的作用

### Progressive Tandem Learning for Pattern Recognition with Deep Spiking Neural Networks

钉状神经网络（SNN）由于其事件驱动的特性和稀疏的通信，相对于传统的人工神经网络（ANN）具有低延迟和高计算效率的明显优势。但是，深度SNN的训练并不简单。在本文中，我们提出了一种新颖的ANN到SNN转换和分层学习框架，用于快速有效的模式识别，这被称为深度SNN的渐进串联学习。通过研究离散表示空间中ANN和SNN之间的等价关系，引入了一种原始网络转换方法，该方法充分利用了尖峰计数来近似模拟神经元的激活值。为了补偿由原始网络转换引起的近似误差，我们进一步引入了带有自适应训练调度器的逐层学习方法，以对网络权重进行微调。渐进式串联学习框架还允许在训练过程中逐步施加硬件限制，例如有限的重量精度和扇入连接。经过如此训练的SNN在大规模目标识别，图像重建和语音分离任务上表现出了卓越的分类和回归能力，同时与其他最新的SNN相比，其推理时间和突触操作至少减少了一个数量级。实现。因此，它为功耗有限的普及型移动和嵌入式设备带来了无数的机会

### Multivariate Time Series Classification Using Spiking Neural Networks

随着物联网（IoT）和网络物理系统（CPS）的发展和壮大，在嵌入式设备等能源受限的情况下，处理时间数据流的需求日益增长。尖峰神经网络已引起关注，因为它通过将信息编码和处理为稀疏尖峰事件来实现低功耗，可将其用于事件驱动的计算。最近的工作还显示了SNN处理空间时间信息的能力。功率受限的设备可以利用这些优势来处理实时传感器数据。但是，大多数现有的SNN训练算法都专注于视觉任务，并且暂时的功课分配没有得到解决。此外，广泛采用的速率编码会忽略时间信息，因此不适合表示时间序列。在这项工作中，我们提出了一种将时间序列转换为稀疏的空间时间峰值模式的编码方案。还提出了一种对空间时间模式进行分类的训练算法。在UCR存储库中的多个时间序列数据集上评估了所提出的方法，并获得了与深度神经网络相当的性能

### BS4NN: Binarized Spiking Neural Networks with Temporal Coding and Learning

我们最近提出了S4NN算法，本质上是向后传播对多层尖峰神经网络的一种适应，该多层尖峰神经网络使用简单的非漏电积分和发射神经元以及一种称为“第一次尖峰时间”编码的时间编码形式。使用这种编码方案，神经元每个刺激最多激发一次，但是激发顺序会携带信息。在这里，我们介绍BS4NN，这是对S4NN的修改，其中突触权重被限制为二进制（+1或-1），以减少内存和计算的占用空间。这是使用两组权重完成的：首先，通过梯度下降更新的实值权重，用于反向传播的反向传递；其次，正向权重使用它们的正负号。类似的策略已用于训练（非加标）二值化神经网络。主要区别在于BS4NN在时域中运行：尖峰顺序传播，并且不同的神经元可能在不同的时间达到其阈值，从而增加了计算能力。我们在MNIST和Fashion MNIST这两个流行基准上对BS4NN进行了验证，并获得了此类网络的最新准确性（分别为97.0％和87.3％），相对于实际值权重（0.4 ％和0.7％）。我们还证明了BS4NN在这两个数据集上具有相同体系结构的性能优于简单BNN（分别为0.2％和0.9％），这大概是因为它利用了时间维度

### Long Short-Term Memory Spiking Networks and Their Applications

基于事件的神经形态系统的最新进展引起了对尖峰神经网络（SNN）的使用和开发的极大兴趣。但是，尖峰神经元的不可区分性质使SNN与常规反向传播技术不兼容。尽管在训练常规深度神经网络（DNN）方面取得了显着进展，但对SNN的训练方法仍然知之甚少。在本文中，我们提出了一种训练递归SNN的新颖框架。类似于递归神经网络（RNN）在DNN中学习时间序列模型中提供的好处，我们基于长短期记忆（LSTM）网络开发SNN。我们表明，LSTM尖峰网络学习尖峰的时序和时间依赖性。我们还开发了一种基于LSTM的SNN中错误反向传播的方法。在基于LSTM的SNN中进行反向传播的已开发体系结构和方法使他们能够学习长期依存关系，其结果与传统LSTM相当

 

### Neuromorphic Processing and Sensing: Evolutionary Progression of AI to Spiking

机器学习和深度学习应用程序的不断增长，需要越来越多的计算资源才能成功满足始终连接的自动化世界不断增长的需求。基于尖峰神经网络算法的神经形态技术有望通过模拟人脑的功能和峰值来利用少量的计算和功率需求来实现高级人工智能。随着工具和平台的泛滥，帮助数据科学家和机器学习工程师开发人工和深度神经网络的最新创新，向新范式的过渡将需要从现有的良好基础上进行构建。本文解释了基于尖峰的神经形态技术的理论工作，并概述了硬件处理器，软件平台和神经形态传感设备的最新技术。为当前的机器学习专家更新他们的技能，以及从当前一代的深度神经网络到SNN的分类或预测模型铺平了道路。这可以通过利用SpiNNaker和Nengo迁移工具包形式的现有专用硬件来实现。第一手分享了将VGG-16神经网络转换为SNN的实验结果。可以轻松受益于SNN的工业，医学和商业应用的前瞻性眼光，将这项研究总结为神经形态计算的未来

### Leaky Integrate-and-Fire Spiking Neuron with Learnable Membrane Time Parameter

尖刺神经网络（SNN）由于其瞬时信息处理能力，低功耗和高生物似然性而吸引了研究兴趣。泄漏集成并发射（LIF）神经元模型是SNN中最流行的尖峰神经元模型之一，因为它可以在计算成本和生物学可信度之间取得平衡。 LIF神经元的最重要参数是膜时间常数，它确定膜电位的衰减率。 $ \ tau $的值在包含LIF神经元的SNN中起着至关重要的作用。但是，$ \ tau $通常被视为超参数，它在训练SNN之前预先设置并手动调整。在本文中，我们提出了一种新型的尖峰神经元，即参数泄漏积分与发射（PLIF）神经元，其$ \ tau $是可学习的参数，而不是经验的超参数。我们评估具有PLIF神经元的SNN在传统静态MNIST，Fashion-MNIST，CIFAR-10数据集和神经形态N-MNIST，CIFAR10-DVS数据集上的图像分类任务的性能。实验结果表明，PLIF神经元增强的SNN优于传统的尖峰神经元

 

### FSpiNN: An Optimization Framework for Memory- and Energy-Efficient Spiking Neural Networks

尖峰神经网络（SNN）由于其事件驱动的处理而引起了人们的兴趣，这种事件驱动处理可能消耗硬件平台中的低功耗/能量计算，同时由于尖峰时序相关的可塑性（STDP）规则而提供无监督的学习能力。但是，最新的SNN需要占用大量内存才能实现高精度，从而使其难以部署在嵌入式系统上，例如在电池供电的移动设备和IoT Edge节点上。为此，我们提出了FSpiNN，这是一种用于获取用于训练和推理处理的内存和高能效SNN的优化框架，具有无监督的学习能力，同时又能保持准确性。它是通过（1）减少神经元和STDP操作的计算要求，（2）提高基于STDP的学习的准确性，（3）通过定点量化压缩SNN，以及（4）合并内存和优化过程中的能源需求。 FSpiNN通过减少神经元操作的次数，基于STDP的突触权重更新和STDP复杂度来减少计算需求。为了提高学习的准确性，FSpiNN采用基于时间步长的突触权重更新，并自适应确定STDP增强因子和有效抑制强度。实验结果表明，与最新技术相比，在整个MNIST中，FSpiNN节省了7.5倍的内存，并且将训练的能量效率平均提高了3.5倍，将推理的能量效率提高了1.8倍和时尚MNIST数据集，对于具有4900个兴奋性神经元的网络不会造成任何准确性损失，从而为边缘设备/嵌入式系统启用了节能型SNN

 

### A Hybrid Neuromorphic Object Tracking and Classification Framework for Real-time Systems

深度学习推理很大程度上需要在“边缘”上进行，这是高度计算和内存密集型工作负载，因此对于低功耗嵌入式平台（如移动节点和远程安全应用程序）而言，它是很难处理的。为了解决这一挑战，本文提出了一种实时的，混合的神经形态框架，用于使用基于事件的摄像机进行对象跟踪和分类，该摄像机具有诸如低功耗（5-14 mW）和高动态范围（120 dB）之类的属性。但是，与使用逐事件处理的传统方法不同，这项工作使用混合框架和事件方法来实现高性能节能。使用基于前景事件密度的基于框架的区域建议方法，在解决遮挡场景时，使用视在对象速度实现了硬件友好的对象跟踪方案。通过高能效的深层网络（EEDN）管道，将对象轨迹输入转换回峰值以进行TrueNorth分类。使用原始收集的数据集，我们在硬件跟踪输出上训练TrueNorth模型，而不是像通常那样使用地面真实对象的位置，并演示了我们的系统处理实际监视场景的能力。作为一种可选范例，为了利用神经形态视觉传感器（NVS）的低延迟和异步特性，我们还提出了一种采用C ++实现的连续时间跟踪器，其中每个事件都得到单独处理。因此，我们将提出的方法与最新的基于事件的事件和基于帧的对象跟踪和分类方法进行了比较，并演示了我们的神经形态方法在实时和嵌入式应用中的使用案例，而不会牺牲性能。最后，在数小时的行车记录评估中，我们还展示了建议的系统对标准RGB摄像机设置的功效

 

### Multi-Compartment Variational Online Learning for Spiking Neural Networks

尖峰神经网络（SNN）提供了一种新颖的计算范例，该范例通过递归处理和二进制神经激活来捕获生物大脑进行推理和学习的效率。现有的大多数用于SNN的训练算法都采用了尖峰神经元模型，其中神经元根据内部状态变量（称为膜电位）的动力学输出单个峰值。本文探讨了一个更通用的模型，其中每个尖峰神经元包含多个间隔，每个间隔跟踪一个独特的膜电位的动态，同时在各个间隔中共享相同的突触权重。事实证明，基于概率广义线性神经模型的学习规则可以通过基于重要性加权或广义期望最大化的现代变异推理来利用多个部分的存在。关键思想是使用神经隔室对来自隐藏神经元的多个独立尖峰信号进行采样，以便获得对似然训练准则的更好统计估计。导出的在线学习算法遵循具有全局学习信号的三要素规则。具有标准神经形态数据集的结构化输出记忆任务和分类任务的实验结果表明，随着隔间数量的增加，准确性和校准方面也有了显着提高

 

### Supervised Learning in Temporally-Coded Spiking Neural Networks with Approximate Backpropagation

在这项工作中，我们提出了一种新的监督学习方法，用于对时间编码的多层尖峰网络进行分类。 该方法采用了模拟反向传播的增强信号，但是计算强度却低得多。 除此信号外，每一层的权重更新计算仅需要本地数据。 我们还采用了能够产生特定输出峰值序列的规则； 通过将目标尖峰时间设置为等于实际尖峰时间，并为关键的高价值神经元设置一个略微的负偏移量，则实际尖峰时间将尽可能早。 在模拟的MNIST手写数字分类中，使用此规则训练的两层网络与基于反向传播的非尖峰网络的性能相匹配

 

### Online spatio-temporal learning in deep neural networks

生物神经网络具有通过在线学习不断适应的内在能力。这方面与将误差反向传播（BPTT）应用于递归神经网络（RNN）或最近甚至应用于生物学启发的尖峰神经网络（SNN）的学习形成了鲜明的对比，因为BPTT的持续时间扩展会导致系统-锁定问题。在线学习最近重新引起了研究界的关注，重点放在近似BPTT的方法或在SNN中应用的生物学上可行的方案上。在这里，我们提出了一个基于空间和时间梯度分量的清晰分离的替代观点。结合生物学的见解，我们从第一原理中得出了一种新颖的在线学习算法，称为在线时空学习（OSTL），该算法与浅层网络的BPTT梯度等效。我们将OSTL应用于SNN，允许它们首次使用BPTT等效梯度在线进行训练。此外，提出的公式还揭示了一类可在线以低复杂度进行训练的SNN架构。此外，我们将OSTL扩展到深层网络，同时保持其关键特性。除SNN外，OSTL的通用形式还适用于广泛的网络体系结构，包括包含长短期内存（LSTM）和门控循环单元（GRU）的网络。我们演示了我们的算法在从语言建模到语音识别等各种任务上的操作，并获得了与BPTT基线相当的结果。所提出的算法为开发用于SNN和一般深度RNN的简洁有效的在线培训方法提供了框架

 

### A new GPU library for fast simulation of large-scale networks of spiking neurons

在过去的十年中，人们对并行硬件系统的开发越来越感兴趣，这些并行硬件系统用于模拟尖峰神经元的大规模网络。与其他高度并行的系统相比，GPU加速的解决方案具有成本相对较低且用途广泛的优势，这还归功于可以使用CUDA-C / C ++编程语言。 NeuronGPU是一个GPU库，用于基于新型的峰值传递算法，以C ++和CUDA-C ++编程语言编写，用于对尖峰神经网络模型进行大规模仿真。该库包括简单的LIF（泄漏集成和发射）神经元模型，以及多个具有基于电流或电导的突触的多突触AdEx（自适应指数集成和发射）神经元模型，用户可定义的模型和不同的设备。通过以CUDA-C ++编写的并行五阶Runge-Kutta方法和自适应步长控制方法，可以对AdEx模型动力学微分方程进行数值求解。在这项工作中，我们基于AdIF神经元和基于电导的基于LIF神经元和基于电流的突触，以及基于兴奋性和抑制性神经元的平衡网络对著名的皮质微电路模型进行仿真，从而评估该库的性能。突触。在这些模型上，我们将显示，所提出的库在每秒生物活性的模拟时间方面达到了最先进的性能。特别是，使用单个NVIDIA GeForce RTX 2080 Ti GPU板，就可以以非常接近实时的速度模拟完整的皮质微电路模型，其中包括大约77,000个神经元和3个cdot 10 ^ 8 $连接。而1,000,000个AdEx神经元与每个神经元1,000个连接的平衡网络的仿真时间约为每秒70 s生物活动

 

### DIET-SNN: Direct Input Encoding With Leakage and Threshold Optimization in Deep Spiking Neural Networks

具有生物启发性的尖峰神经网络（SNN），通过随时间分布的异步二进制信号（或尖峰）运行，可以潜在地提高事件驱动硬件的计算效率。由于输入编码效率低下以及神经元参数（触发阈值和膜泄漏）设置欠佳，导致最新的SNN遭受高推理延迟。我们提出了DIET-SNN，这是一种低延迟的深脉冲网络，该网络经过梯度下降训练，可优化膜泄漏和触发阈值以及其他网络参数（权重）。通过端到端反向传播优化了SNN每一层的膜泄漏和阈值，从而在减少延迟的情况下实现了竞争性精度。图像的模拟像素值直接应用于DIET-SNN的输入层，而无需转换为峰值序列。信息在第一卷积层中转换为尖峰，在此处泄漏积分和发射（LIF）神经元对加权输入进行积分，并在膜电位超过训练的发射阈值时产生输出尖峰。受过训练的膜泄漏控制输入信息的流动并衰减不相关的输入，以增加网络的卷积和线性层中的激活稀疏性。减少的等待时间与高激活稀疏性相结合，大大提高了计算效率。我们评估来自VIF和ResNet架构上的CIFAR和ImageNet数据集的图像分类任务上的DIET-SNN。我们在ImageNet数据集上以25个时间步长（推理延迟）实现了66.52％的top-1准确性，其计算能力比等效的标准ANN少3.1倍。此外，与其他最新的SNN模型相比，DIET-SNN的推理速度提高了5-100倍

 

### TCL: an ANN-to-SNN Conversion with Trainable Clipping Layers

尖峰神经网络（SNN）提供的功耗比深度神经网络（DNN）（在本文中称为模拟神经网络（ANN））低得多。 按照惯例，SNN无法达到ANN的训练精度。 然而，最近的一些研究表明，可以通过将ANN转换为SNN而不是直接训练SNN来解决这一挑战。尽管如此，SNN的大延迟仍然限制了其应用，对于像Imagenet这样的大型数据集，它更具问题性。 克服这一问题是一项挑战，因为在SNN中，其准确性和延迟之间存在折衷关系。 在这项工作中，我们通过使用称为TCL的可训练裁剪器优雅地缓解了该问题。 通过将TCL与传统的数据规范化技术相结合，在经过250个周期的延迟约束的ANN到SNN转换后，我们分别获得VGG-16和RESNET-34的71.12％和73.38％（在ImageNet上）

### Adaptive Object Detection with Dual Multi-Label Prediction

尖峰神经网络（SNN）在异步离散事件（或尖峰）下运行，这可能会导致神经形态硬件实现中的更高能效。许多工作表明，可以通过从训练有素的人工神经网络（ANN）复制权重并将每一层的触发阈值设置为该层中接收到的最大输入来形成推理的SNN。这些类型的转换后的SNN需要大量的时间步才能达到具有竞争力的精度，从而降低了节能效果。可以通过从头开始使用基于尖峰的反向传播训练SNN来减少时间步数，但这在计算上昂贵且缓慢。为了解决这些挑战，我们提出了一种针对深度SNN的高效计算训练技术。我们提出一种混合训练方法：1）采用转换后的SNN，并将其权重和阈值用作基于尖峰的反向传播的初始化步骤，以及2）在这个经过仔细初始化的网络上执行增量尖峰时序相关的反向传播（STDB），以获得SNN在几个纪元内收敛并且需要较少的时间步进行输入处理。 STDB通过使用神经元的尖峰时间定义的新型替代梯度函数执行。对于大多数标准图像分类数据集，所提出的训练方法收敛于少于20个基于尖峰的反向传播时间，因此与从头训练SNN相比，极大地降低了训练复杂度。我们针对VGG和ResNet架构在CIFAR-10，CIFAR-100和ImageNet数据集上进行了实验。我们使用250个时间步在SNN上实现ImageNet数据集的top-1精度为65.19％，与具有类似精度的转换SNN相比快了10倍

### Supervised Learning with First-to-Spike Decoding in Multilayer Spiking Neural Networks

 

实验研究支持大脑中基于尖峰的神经元信息处理的概念，其中神经回路表现出范围广泛的基于时间的编码策略，可以快速有效地表示感觉刺激。因此，期望将基于尖峰的计算应用于应对现实世界的挑战，特别是将这种理论转移到用于低功率嵌入式应用的神经形态系统。因此，我们提出了一种新的监督学习方法，该方法可以训练基于快速，先到先得的解码策略的多层尖峰神经网络来解决分类问题。拟议的学习规则支持由随机隐藏神经元触发的多个峰值，但通过依赖确定性输出层生成的首次峰值响应而保持稳定。除此之外，我们还探索了几种不同的，基于峰值的编码策略，以形成所呈现输入数据的紧凑表示。我们展示了应用于多个基准数据集（包括MNIST）的学习规则的分类性能。学习规则能够根据数据进行概括，并且即使与包含很少的输入层和隐藏层神经元的受约束的网络体系结构一起使用时也成功。此外，我们重点介绍了一种新颖的编码策略，称为“扫描线编码”，可以将图像数据转换为紧凑的时空模式以用于后续的网络处理。设计受约束但最优化的网络结构并降低输入维数对神经形态应用具有重要意义

### TactileSGNet: A Spiking Graph Neural Network for Event-based Tactile Object Recognition

触觉对于各种机器人任务（包括抓握和手动操作）至关重要。灵活的，事件驱动的电子皮肤的新进展可能很快使机器人具有与人类相似的触摸感知功能。这些电子皮肤会异步响应变化（例如压力，温度），并且可以不规则地放置在机器人的身体或末端执行器上。但是，这些独特的功能可能会使当前的深度学习方法（例如卷积特征提取器）不适合触觉学习。在本文中，我们提出了一种新型的基于事件的触觉目标识别的峰值图神经网络。为了利用紫杉的局部连通性，我们提出了几种在图结构中组织触觉数据的方法。基于构造的图，我们开发了尖峰图卷积网络。尖峰神经网络的事件驱动性质使其可以说更适合于处理基于事件的数据。在两个触觉数据集上的实验结果表明，所提出的方法优于其他最新的尖峰方法，在对各种不同的家用物体进行分类时，可达到约90％的高精度







## 2020.6

### Unifying Activationand Timing-based Learning Rules for Spiking Neural Networks

为了在尖峰神经网络（SNN）训练中跨时域进行梯度计算，已经分别研究了两种不同的方法。 第一个是针对尖峰激活的变化来计算梯度（基于激活的方法），第二个是针对尖峰定时的变化来计算梯度（基于定时的方法）。 在这项工作中，我们对这两种方法进行了比较研究，并提出了一种将它们结合起来的新的监督学习方法。 所提出的方法通过像在基于时序的方法中那样移动尖峰时序以及在基于激活的方法中生成和消除尖峰，可以更有效地利用每个单独的尖峰。 实验结果表明，该方法在准确性和效率上都比以前的方法具有更高的性能

### Training Deep Spiking Neural Networks

与目前的模拟神经网络（ANN）相比，使用具有神经形态硬件的脑启发性尖峰神经网络（SNN）进行计算可以提供更高的数量级能源效率。不幸的是，训练具有与最新的ANN相同层数的SNN仍然是一个挑战。据我们所知，在这方面唯一成功的方法是对ANN进行监督训练，然后将其转换为SNN。在这项工作中，我们直接使用带有替代梯度的反向传播训练深层SNN，发现由于前馈SNN的隐式递归性质，爆炸或消失梯度问题严重阻碍了它们的训练。我们表明可以通过调整代理梯度函数来解决此问题。我们还建议使用来自ANN文献的批处理归一化SNN神经元的输入电流。使用这些改进，我们表明可以在CIFAR100和Imagenette对象识别数据集上使用ResNet50体系结构训练SNN。与从ANN转换而来的SNN相比，经过训练的SNN在精度上落后于类似的ANN，但推理时间步长要小几个数量级（低至10）才能达到良好的准确性，而SNN的转换需要大约1000个时间步长

 

### Self-organization of multi-layer spiking neural networks

在早期开发过程中，我们大脑中的活动神经网络会自动自我组织成大型，复杂的体系结构，从而形成有组织且功能强大的有机计算设备。能够在发育中的大脑中形成复杂体系结构的关键机制是，大脑中不断发展的神经元活动时空时空波的出现。受此策略的启发，我们尝试有效地将具有任意层的大型神经网络自组织成各种体系结构。为了实现这一目标，我们提出了一种动态系统形式的模块化工具包，可以无缝堆叠以组装多层神经网络。动力学系统封装了尖峰单元，其层间/层间交互作用以及控制层之间信息流的可塑性规则的动力学。我们的工具包的主要功能是：（1）由上一层的活动触发的跨多个层的自主时空波；（2）依赖于时序的可塑性（STDP）学习规则，可根据以下内容更新层间连接连接层中的波浪活动。我们的框架导致了从多层感知器到自动编码器的各种体系结构的自组织。我们还证明了涌现的波可以自我组织尖峰网络体系结构以执行无监督学习，并且网络可以与线性分类器耦合以对经典图像数据集（如MNIST）执行分类。从广义上讲，我们的工作表明，可以使用动态的学习系统框架来自组织大型计算设备

 

### Training spiking multi-layer networks with surrogate gradients on an analog neuromorphic substrate

尖峰神经网络是自然的解决方案，用于以较低的新陈代谢能量成本以较高的时间精度进行并行信息处理。为此，生物神经元将输入作为模拟总和进行集成，并以尖峰（即时间上稀疏的二进制事件）以数字方式传达其输出。这些体系结构原理可以有效地反映在模拟神经形态硬件中。然而，在硬件设备上以稀疏活动来训练尖峰神经网络仍然是一个重大挑战。主要原因是缺乏适当的训练方法，这些方法考虑到了特定于设备的缺陷，并且以单个峰值而不是发射速率运行。为解决此问题，我们开发了一种硬件在环策略，可在模拟BrainScales-2芯片上使用替代梯度来训练多层尖峰网络。具体来说，我们使用硬件来计算网络的前向通过，而后向通过软件来计算。我们在缩小的MNIST 16x16版本和时尚的MNIST数据集中评估了我们的方法，其中尖峰延迟编码像素强度。模拟神经形态底物与软件中实现的等效大小网络的性能非常匹配。它每秒能够处理70 k个图案，而功耗却不到300 mW。增加的活动规范化导致网络活动稀疏，每个输入约20个峰值，分类性能几乎没有下降。因此，总的来说，我们的工作演示了在模拟神经形态基质上的低能量尖峰网络处理，并在分类准确性，处理速度和效率方面为硬件系统树立了多个新的基准。重要的是，我们的工作强调了硬件在环训练的价值，并为非von-Neumann架构上的节能信息处理铺平了道路

 

### Towards Understanding the Effect of Leak in Spiking Neural Networks

正在探索尖峰神经网络（SNN），以模拟人脑的惊人功能，该功能可以通过嘈杂的尖峰活动来稳健而高效地学习和计算功能。已经提出了多种尖峰神经元模型以类似于生物学神经元功能。这些模型具有不同的生物保真度，通常在内部状态中包含一个泄漏路径，称为膜电位。尽管人们认为渗漏模型具有更高的生物可行性，但从纯粹的计算角度来看，有渗漏模型与无渗漏模型之间的比较分析仍需引起注意。在本文中，我们调查有关泄漏合理性的问题以及使用泄漏行为的利弊。我们的实验结果表明，与没有泄漏的模型相比，泄漏的神经元模型具有更高的鲁棒性和更好的泛化能力。但是，与一般概念相反，泄漏会降低计算的稀疏性。通过频域分析，我们证明了泄漏在消除输入中的高频成分方面的效果，从而使SNN能够更强大地抵抗噪声尖峰输入

### You Only Spike Once: Improving Energy-Efficient Neuromorphic Inference to ANN-Level Accuracy

在过去的十年中，人工神经网络（ANN）的进步使它们在执行各种任务时表现出色。实际上，例如，当执行图像识别时，它们已经达到了人类平等。不幸的是，这些人工神经网络的准确性是以大量的高速缓存和/或存储器访问以及计算操作为代价的。尖刺神经网络（SNN）是一种神经形态或受大脑启发的网络，最近由于作为ANN的高效替代品而倍受关注，因为它们稀疏，访问权重很小，并且通常仅使用加法运算来代替更耗电的乘法和累加（MAC）操作。绝大多数神经形态硬件设计都支持速率编码的SNN，其中信息以尖峰速率编码。速率编码的SNN可能被视为编码方案效率不高，因为它涉及大量尖峰的传输。一种更有效的编码方案，即首次尖峰时间（TTFS）编码，以尖峰到达的相对时间编码信息。尽管TTFS编码的SNN比速率编码的SNN效率更高，但到目前为止，与以前的方法相比，它们在准确性方面的表现很差。

 因此，在这项工作中，我们旨在克服TTFS编码的神经形态系统的局限性。为实现此目的，我们提出：（1）一种用于从ANN转换为TTFS编码的SNN的新型优化算法，以及（2）一种用于TTFS编码的SNN的新型硬件加速器，具有可扩展的低功耗设计。

总体而言，我们在TTFS编码和培训方面的工作提高了SNN的准确性，从而在MNIST MLP上获得了最新的结果，同时与最新的神经形态硬件相比，功耗降低了1.29％

 

### An Efficient Spiking Neural Network for Recognizing Gestures with a DVS Camera on the Loihi Neuromorphic Processor

Loihi神经形态处理器上的DVS相机识别手势的高效尖峰神经网络

 

### Learning Precise Spike Timings with Eligibility Traces

尖峰神经网络（SNN）领域的最新研究表明，SNN的递归变量，即长短期SNN（LSNN），可以像LSTM一样通过误差梯度进行训练。基本的学习方法（e-prop）基于适用于泄漏整合和解雇（LIF）神经元的合格跟踪的形式化。在这里，我们表明，提出的方法不能完全展现出与尖峰时间相关的可塑性（STDP）。结果，这从原则上限制了SNN的固有优势，即开发依赖于精确的相对尖峰定时的代码的潜力。我们显示，当从稍微复杂的尖峰神经元模型（此处为Izhikevich模型）导出时，STDP感知的突触梯度自然会出现在e-prop的资格方程式中。我们还提出了提供相似梯度的LIF模型的简单扩展。在一个简单的实验中，我们证明了STDP感知的LIF神经元可以从基于e-prop的梯度信号中学习精确的尖峰定时

 

### Always-On, Sub-300-nW, Event-Driven Spiking Neural Network based on Spike-Driven Clock-Generation and Clockand Power-Gating for an Ultra-Low-Power Intelligent Device

永远在线的人工智能（AI）功能（例如关键字搜索（KWS）和视觉唤醒）往往在超低功耗设备中占总功耗的主导地位。 一个关键的观察是，常开功能的信号在时间上是稀疏的，尖峰神经网络（SNN）分类器可以利用它来节省功率，因为SNN的开关活动和功耗往往会随尖峰速率而缩放。 为了实现这一目标，我们提出了一种针对始终在线功能的新颖SNN分类器架构，以具有竞争性的推理精度为KWS和其他始终在线分类工作负载演示了300nW以下的功耗

### Biologically Plausible Learning of Text Representation with Spiking Neural Networks

这项研究提出了一种新的生物学上可行的机制，用于生成基于低维峰值的文本表示形式。 首先，我们演示如何将文档转换为一系列尖峰尖峰序列，随后将其用作尖峰神经网络（SNN）的训练过程中的输入。 该网络由生物学上合理的元素组成，并根据无监督的Hebbian学习规则“峰值定时依赖可塑性（STDP）”进行了训练。 训练后，SNN可用于生成适用于文本/文档分类的低维基于尖峰的文本表示形式。 实证结果表明，生成的文本表示形式可以有效地用于文本分类，从而使20个新闻组数据集的bydate版本的准确度达到$ 80.19 \％$，这在依赖于低维文本表示形式的方法中是一个领先的结果

 



## 2020.5

### Memristors -from In-memory computing, Deep Learning Acceleration, Spiking Neural Networks, to the Future of Neuromorphic and Bio-inspired Computing

机器学习，尤其是以深度学习的形式，已经驱动了人工智能的最新发展。深度学习基于某种程度上受生物启发的计算模型，因为它们依赖于并行运行的连接的简单计算单元的网络。深度学习已成功应用于对象/模式识别，语音和自然语言处理，自动驾驶车辆，智能自我诊断工具，自动驾驶机器人，知识渊博的个人助理和监控等领域。这些成功主要受到三个因素的支持：海量数据的可用性，计算能力的持续增长以及算法创新。摩尔定律的逐渐消亡以及随之而来的通过缩放可以实现的计算能力预期的适度改进，提出了以下问题：由于硬件限制，上述进度会减慢还是停止。本文回顾了超越CMOS硬件技术的新型忆阻器的案例，该忆阻器是实现节能型内存计算，深度学习加速器和增强型神经网络的潜在解决方案。中心主题是对非von-Neumann计算体系结构的依赖以及对开发量身定制的学习和推理算法的需求。为了论证来自生物学的经验教训可以为人工智能的进一步发展提供指导，我们简要讨论了一个基于示例的储层计算。我们通过推测未来的神经形态和大脑启发式计算系统的全景来结束本综述

### Distilling Spikes: Knowledge Distillation in Spiking Neural Networks

尖峰神经网络（SNN）是节能的计算体系结构，与经典的人工神经网络（ANN）不同，它交换尖峰来处理信息。因此，SNN更适合实际部署。但是，类似于ANN，SNN还可从更深的架构中受益，以获得更高的性能。此外，像深度ANN一样，SNN的内存，计算量和功耗要求也会随着模型大小的增加而增加，因此模型压缩成为必要。知识蒸馏是一种模型压缩技术，可以将大型机器学习模型的学习转移到较小的模型，而性能损失最小。在本文中，我们提出了在尖峰神经网络中用于图像分类任务的知识蒸馏技术。我们提出了从较大的SNN（也称为教师网络）到较小的SNN（也称为学生网络）中提取峰值的方法，同时将对分类准确性的影响降至最低。我们在三个标准数据集上进行了详细的实验，证明了该方法的有效性，同时提出了新颖的蒸馏方法和损失函数。我们还提出了一种使用中间网络从学生网络获得更高性能的SNN多阶段知识提炼技术。我们的方法有望为在资源受限的硬件平台上部署高性能大型SNN模型开辟新途径

### Towards Efficient Processing and Learning with Spikes: New Approaches for Multi-Spike Learning

尖峰是中枢神经系统中用于信息传输和处理的货币。人们还认为它们在生物系统的低功耗中起着至关重要的作用，其效率越来越受到人们对神经形态计算领域的关注。但是，有效处理和学习离散尖峰仍然是一个具有挑战性的问题。在本文中，我们朝着这个方向做出了贡献。首先引入简化的突触神经元模型，其中突触输入和触发输出对通过脉冲函数建模的膜电位的影响。然后提出一种事件驱动方案，以进一步提高处理效率。基于神经元模型，我们提出了两个新的多钉学习规则，它们在各种任务（包括关联，分类，特征检测）上表现出比其他基准更好的性能。除了效率外，我们的学习规则还显示出对各种类型强噪声的高鲁棒性。对于分类任务，它们也可以推广到不同的峰值编码方案，尤其是单个神经元能够根据我们的学习规则解决多类别的分类。在特征检测任务中，我们重新检查了无监督STDP的能力及其局限性，并发现了一种失去选择性的新现象。相反，我们提出的学习规则可以在广泛的条件下可靠地解决任务，而无需应用特定的约束。而且，我们的规则不仅可以检测特征，而且可以区分特征。我们方法的改进性能将有助于神经形态计算的首选

 

### Spiking Neural Networks Hardware Implementations and Challenges: a Survey

因此，神经形态计算是学术和工业参与者的主要研究领域。与冯·诺依曼（Von Neumann）机器相反，受大脑启发的处理器旨在使存储器和计算元素更接近，以有效地评估机器学习算法。最近，Spiking神经网络（使用模拟神经元和突触操作原理的计算原语的一代认知算法）已成为深度学习的重要组成部分。它们有望提高神经网络的计算性能和效率，但最适合能够支持其时态动态的硬件。在这项调查中，我们介绍了尖峰神经网络的硬件实现的最新技术以及从模型选择到训练机制的算法细化的当前趋势。现有解决方案的范围很广；因此，我们提出了总体框架并逐案研究相关的特殊性。我们描述了在硬件级别利用这些事件驱动算法的特征的策略，并讨论了它们的相关优势和挑战

 

### Constructing Accurate and Efficient Deep Spiking Neural Networks with Double-threshold and Augmented Schemes

尖峰神经网络（SNN）被认为是克服当前挑战（例如人工神经网络（ANN）遇到的高功耗）的潜在候选者，但是在实际任务的识别精度方面，它们之间仍然存在差距。因此，最近引入了一种转换策略，通过将经过训练的ANN映射到SNN来弥合这种差距。但是，仍然不清楚，这种获得的SNN可以在多大程度上受益于ANN的准确性优势和基于尖峰的计算范式的高效率。在本文中，我们提出了两种新的转换方法，即TerMapping和AugMapping。 TerMapping是具有双阈值方案的典型阈值平衡方法的直接扩展，而AugMapping还结合了新的增强型尖峰方案，该方案使用尖峰系数来承载出现在以下位置的典型全有或无尖峰的数量一个时间步。我们检查了基于MNIST，Fashion-MNIST和CIFAR10数据集的方法的性能。结果表明，提出的双阈值方案可以有效地提高转换后的神经网络的精度。更重要的是，与其他最新方法相比，拟议的AugMapping在构造准确，快速和高效的深度SNN方面更具优势。因此，我们的研究为在ANN中进一步集成高级技术提供了新方法，以提高SNN的性能，这对于基于基于尖峰的神经形态计算的应用开发可能具有重大意义

### ST-MNIST -- The Spiking Tactile MNIST Neuromorphic Dataset

触觉是智能机器人的基本模式，因为它使它们能够与周围环境中的物理对象灵活交互。电子皮肤的最新进展导致开发了利用这种重要的感觉方式的数据驱动的机器学习方法。但是，用于训练此类算法的当前数据集仅限于标准同步触觉传感器。主要由于大型基于事件的触觉传感器的匮乏，缺乏基于神经形态事件的触觉数据集。拥有这样的数据集对于开发和评估处理时空事件数据的新算法至关重要。例如，在基于常规帧的数据集上评估尖峰神经网络被认为是次优的。在这里，我们首次亮相了一个新的神经形态触觉MNIST（ST-MNIST）数据集，其中包含人类参与者在神经形态触觉传感器阵列上书写而获得的手写数字。我们还描述了使用现有的人工和尖峰神经网络模型评估ST-MNIST数据集的初步工作。本文提供的分类精度可以用作将来工作的性能基准。我们预计我们的ST-MNIST数据集将对神经形态学和机器人学研究领域产生兴趣并有所帮助

### Synaptic Learning with Augmented Spikes

传统的神经元模型将模拟值用于信息表示和计算，而尖峰则采用全有或全无的尖峰。有了更像大脑的处理范例，尖峰神经元在提高效率和计算能力方面更有希望。它们扩展了全有或全无峰值的传统神经元的计算时间。从模拟值的准确性和尖峰的时间处理能力中都能受益吗？在本文中，我们引入了增强尖峰的概念，除了尖峰延迟外，还可以携带带有尖峰系数的补充信息。提出了新的增强尖峰神经元模型和突触学习规则来处理和学习增强尖峰的模式。我们对方法的特性和特征提供系统的见解，包括增强尖峰模式的分类，学习能力，因果关系的构建，特征检测，鲁棒性和对实际任务（如声学和视觉模式识别）的适用性。出色的结果突出了我们方法的有效性和潜在优点。重要的是，我们的增强方法是通用的，可以轻松地推广到其他基于峰值的系统，从而为它们的潜在发展做出了贡献，包括神经形态计算

### Training spiking neural networks using reinforcement learning

与人工神经网络中的连续信号传输相反，大脑中的神经元通过离散的动作尖峰彼此通信。因此，依赖于激活函数的微分性假设的用于神经网络中参数优化的传统技术不再适用于对大脑中的学习过程进行建模。在这个项目中，我们提出了反向传播的生物学上可行的替代方案，以促进尖峰神经网络的训练。我们主要专注于研究强化学习（RL）规则的候选资格，以解决时空学分分配问题，以便在复杂任务中做出决策。在一种方法中，我们将多层神经网络中的每个神经元视为形成特征空间的不同表示形式的独立RL代理，而将网络作为一个整体形成解决当前任务的复杂策略的表示形式。在其他方法中，我们应用了重新参数化技巧，可以在尖峰神经网络中通过随机变换进行区分。我们将这两种方法应用于传统的RL域（例如gridworld，cartpole和山地车）进行比较和对比。此外，我们还建议进行改进和改进，以促进该领域的未来研究

 

### Effective and Efficient Computation with Multiple-timescale Spiking Recurrent Neural Networks

受大脑启发的神经形态计算作为边缘AI范式的出现正促使人们寻求在该硬件上运行高性能且高效的尖峰神经网络。但是，与深度学习中的经典神经网络相比，当前的尖峰神经网络在引人注目的领域缺乏竞争优势。在此，对于顺序任务和流任务，我们演示了一种新型的自适应尖峰递归神经网络（SRNN）与其他尖峰神经网络相比如何能够实现最新的性能，并且几乎达到或超过了经典尖峰神经网络的性能。递归神经网络（RNN），同时表现出稀疏的活动。据此，在较艰巨的任务上，与传统RNN相比，我们计算出SRNN的能耗提高了100美元以上。为了实现这一目标，我们将标准和自适应的多时标峰值神经元建模为自循环神经单元，并在PyTorch深度学习框架中利用替代梯度和自动分化来有效地实现反向传播，包括学习重要的峰值神经元参数，使我们的尖峰神经元适应任务

 

## 2020.4.19~4.30

### VOWEL: A Local Online Learning Rule for Recurrent Networks of Probabilistic Spiking Winner-Take-All Circuits

尖峰神经元网络和Winner-Take-All尖峰电路（WTA-SNN）可以检测在时空多值事件中编码的信息。这些是通过关注事件（例如点击）的时间安排以及通过分配给每个事件的分类数值（例如，喜欢或不喜欢）来描述的。其他用例包括从神经形态相机收集的数据中识别对象，该对象在足够大的亮度变化时为每个像素生成带符号的位。用于训练WTA-SNN的现有方案仅限于速率编码解决方案，因此只能检测空间模式。为任意WTA-SNN开发更通用的训练算法将继承训练（二进制）尖峰神经网络（SNN）的挑战。这些最明显地是阈值函数的不可微性，尖峰神经模型的重复行为以及在神经形态硬件中实现反向传播的难度。在本文中，我们为WTA-SNN开发了一种变体在线本地训练规则，称为VOWEL，该规则仅对可见电路利用局部突触前和突触后信息，对隐藏电路利用附加的公共奖励信号。该方法基于概率广义线性神经模型，控制变量和变分正则化。在具有多值事件的现实世界神经形态数据集上的实验结果证明，WTA-SNN优于使用最新技术训练的传统二进制SNN，尤其是在计算资源有限的情况下

 

### Spiking Machine Intelligence: What we can learn from biology and how spiking Neural Networks can help to improve Machine Learning

到目前为止，现代机器学习基于将高维函数拟合到大量数据集的基础，并利用了巨大的硬件资源。 我们表明，受生物启发的神经元模型，例如“整合并发射”（LIF）神经元，提供了新颖而有效的信息编码方式。 它们可以集成到机器学习模型中，并且是提高机器学习性能的潜在目标。 因此，我们系统地分析了LIF神经元。 我们从推导简单的积分方程开始，甚至可以为其分配梯度。 此外，我们证明可以调整“长短期记忆”单元以显示类似的尖峰特性。 此外，LIF单元被应用于图像分类任务，并经过反向传播训练。 通过这项研究，我们希望通过整合生物学原理为当前增强机器智能的努力做出贡献

 



## 2020.3.26~4.18

### Convolutional Spiking Neural Networks for Spatio-Temporal Feature Extraction

由于基于事件的特性，尖峰神经网络（SNN）可以用于低功耗和嵌入式系统（例如新兴的神经形态芯片）。而且，与传统的人工神经网络（ANN）相比，它们具有计算成本低的优点，同时保留了ANN的属性。但是，卷积加标神经网络和其他类型的SNN的时间编码尚待研究。在本文中，我们提供了在旨在利用此特性的实验中对卷积SNN的时空特征提取的见解。我们提出的浅卷积SNN优于诸如C3D，ConvLstm和类似网络之类的最新时空特征提取方法。此外，我们提出了一种新的深层处理体系结构来解决实际问题（特别是分类任务），并且与CIFAR10-DVS上的其他SNN方法相比，该模型实现了卓越的性能。还值得注意的是，训练过程是基于时空反向传播实现的，而ANN到SNN的转换方法将毫无用处

### Enabling Spike-based Backpropagation for Training Deep Neural Network Architectures

尖峰神经网络（SNN）最近已成为一种重要的神经计算范例。但是，典型的浅层SNN架构表达复杂表示的能力有限，而使用输入尖峰训练深层SNN到目前为止尚未成功。已经提出了多种方法来解决该问题，例如将现成的经过训练的深度人工神经网络（ANN）转换为SNN。但是，ANN-SNN转换方案无法捕获尖峰系统的时间动态。另一方面，由于尖峰生成函数的不连续，不可微分的性质，使用输入尖峰事件直接训练深度SNN仍然是一个难题。为了克服这个问题，我们提出了一种近似的导数方法，该方法解决了LIF神经元的泄漏行为。这种方法可以使用基于尖峰的反向传播直接训练深度卷积SNN（带有输入尖峰事件）。我们的实验表明，与其他使用基于尖峰学习训练的SNN相比，在MNIST，SVHN和CIFAR-10数据集中实现最佳分类精度，可以证明在深度网络（VGG和残差体系结构）上基于尖峰学习的有效性。此外，我们分析了基于事件的稀疏计算，以证明所提出的SNN训练方法在尖峰域进行推理操作的功效

### T2FSNN: Deep Spiking Neural Networks with Time-to-first-spike Coding

尖峰神经网络（SNN）由于其高能效特性而引起了人们的极大兴趣，但是缺乏可扩展的训练算法却限制了它们在实际机器学习问题中的适用性。深入研究了深度神经网络到SNN的转换方法，以扩大SNN的适用性。但是，大多数先前的研究尚未充分利用SNN的时空方面，这导致了尖峰次数和推理延迟方面的效率低下。在本文中，我们提出了T2FSNN，该算法使用基于内核的动态阈值和枝晶技术将首次尖峰时间编码的概念引入深度SNN中，以克服上述缺点。此外，我们提出了基于梯度的优化和早期触发方法，以进一步提高T2FSNN的效率。根据我们的结果，与CIFAR-100的最新结果相比，所提出的方法与突发编码相比，可以将推理延迟和尖峰数量减少到22％且小于1％

### Spike-Timing-Dependent Back Propagation in Deep Spiking Neural Networks

深度神经网络（DNN）的成功可以归因于其深层结构，它可以在多个抽象级别上学习不变特征表示。受大脑启发的尖峰神经网络（SNN）使用时空尖峰模式来编码和传输信息，这在生物学上是现实的，并且适合于超低功耗事件驱动的神经形态实现。因此，深度掺入神经网络（DSNN）代表了人工智能中的一个有希望的方向，并有可能从两全其美中受益。但是，由于标准误差反向传播（BP）算法不能直接应用，因此对DSNN的训练具有挑战性。在本文中，我们首先建立了对为什么误差反向传播在DSNN中无法正常工作的理解。为了解决这个问题，我们提出了一种简单而有效的针对尖刺神经元的整流线性突触后电位函数（ReL-PSP），并提出了针对DSNN的尖峰计时相关反向传播（STDBP）学习算法。在提出的学习算法中，单个尖峰的定时用于承载信息（时间编码），并且基于尖峰定时以事件驱动的方式执行学习（反向传播）。实验结果表明，所提出的学习算法在基于尖峰时间的SNN学习算法中达到了最先进的性能。这项工作调查了动态穗定时对信息编码，突触可塑性和决策的贡献，为未来DSNN的设计提供了新的视角

### Genetic Algorithmic Parameter Optimisation of a Recurrent Spiking Neural Network Model

神经网络是复杂的算法，可以对人脑的行为进行松散建模。它们在计算神经科学和人工智能中发挥着重要作用。下一代神经网络模型基于神经元的尖峰定时活动：尖峰神经网络（SNN）。然而，难以搜索和优化SNN中的模型参数。以前使用遗传算法（GA）优化SNN的研究主要集中在简单，前馈或振荡网络上，但是在优化类似皮质的递归SNN方面所做的工作还很少。在这项工作中，我们调查了如何使用GA搜索复发性SNN中的最佳参数，以达到目标神经元群体的放电率，例如如实验观察我们考虑了基于皮质列的SNN，其中包含1000个Izhikevich尖峰神经元，以提高计算效率和生物学现实性。探索的模型参数是神经元偏置的输入电流。首先，我们针对此特定的SNN找到了针对目标人群的平均射击活动的最佳参数值，并且算法收敛了约100代。然后，我们证明了GA的最佳种群规模在〜16-20之间，而返回最佳适应度的交叉率是〜0.95。总体而言，我们已成功展示了在基于循环皮层的SNN中实施GA优化模型参数的可行性

 

### Benchmarking Deep Spiking Neural Networks on Neuromorphic Hardware

随着大学和行业中越来越多的基于事件的神经形态硬件系统的开发，越来越需要通过特定领域的措施来评估其性能。在这项工作中，我们使用将预训练的非加标转换为加标的神经网络的方法，以评估性能损失并测量三种神经形态硬件系统（BrainScaleS，Spikey，SpiNNaker）和通用仿真框架的每次推断能量。 CPU（NEST）和CPU / GPU（GeNN）。对于模拟硬件，我们进一步应用了称为硬件在环训练的重新训练技术来应对设备不匹配的情况。对五个不同的网络执行此分析，包括通过神经结构搜索框架进行自动优化发现的三个网络。我们证明，对于数字实现而言，转换损耗通常低于1％，而对于模拟系统而言，转换损耗则要适度地提高，其好处是每次推论能耗要低得多

### File Classification Based on Spiking Neural Networks

 

在本文中，我们提出了一种基于尖峰神经网络（SNN）的大数据集文件分类系统。通过新颖的相关时间编码方案将键值元数据对中包含的文件信息映射到输入到SNN的尖峰模式。输入峰值模式之间的相关性由文件相似性度量确定。首先解决使用依赖于尖峰时序的可塑性（STDP）的此类网络的无监督训练。然后，通过对误差信号进行反向传播来考虑监督SNN训练，该误差信号是通过将输出神经元处的尖峰模式与代表所需类别的目标模式进行比较而获得的。对具有数万个元素的各种公开可用数据集测量分类准确性，并将其与其他学习算法（包括逻辑回归和支持向量机）进行比较。仿真结果表明，所提出的使用忆阻突触的基于SNN的系统可以代表经典机器学习算法的推理任务，特别是在输入数据异步摄取且资源有限的环境中，是一种有效的替代方法



##  2020.3.14~3.25

### A Power-Efficient Binary-Weight Spiking Neural Network Architecture for Real-Time Object Classification

神经网络硬件被认为是未来边缘设备的重要组成部分。 在本文中，我们为边缘平台上的低功耗实时对象分类提出了一种二进制加权加标神经网络（BW-SNN）硬件体系结构。 该设计在芯片上存储了完整的神经网络，因此不需要芯片外带宽。 拟议的脉动阵列使典型卷积层的数据重用最大化。 在90nm CMOS中实现了5层卷积BW-SNN硬件。 与最新设计相比，每个分类的区域成本和能耗分别降低了7美元和23美元，同时在MNIST基准上也实现了更高的准确性。 这也是支持先进的CNN架构的SNN硬件架构的先驱

 

### Spike-FlowNet: Event-based Optical Flow Estimation with Energy-Efficient Hybrid Neural Networks

ECCV2020

基于事件的摄像机在各种条件下显示出巨大的潜力，例如高速运动检测以及在传统的基于帧的摄像机受到严重影响的弱光环境下实现导航的能力。这归因于其高时间分辨率，高动态范围和低功耗。但是，常规的计算机视觉方法以及深层的模拟神经网络（ANN）都不适合与事件摄像机输出的异步和离散特性一起很好地工作。尖峰神经网络（SNN）是处理事件摄影机输出的理想范例，但是由于尖峰消失现象，深层SNN的性能会受到影响。为了克服这些问题，我们提出了Spike-FlowNet，这是一种将SNN和ANN集成在一起的深度混合神经网络体系结构，可以在不牺牲性能的情况下有效地估计稀疏事件相机输出的光流。该网络在多车立体声事件摄像机（MVSEC）数据集上进行了自我监督学习的端到端培训。 Spike-FlowNet在光流预测能力方面优于其相应的基于ANN的方法，同时提供了显着的计算效率

### Inherent Adversarial Robustness of Deep Spiking Neural Networks: Effects of Discrete Input Encoding and Non-Linear Activations

在最近对可信赖的神经网络的追求中，我们提出了尖峰神经网络（SNN）作为对抗攻击的固有鲁棒性的潜在候选者。在这项工作中，我们证明，对于深度VGG架构上的CIFAR10和CIFAR100数据集，SNN的准确度降级要比不加扰的SNN严重。我们将这种鲁棒性归因于SNN的两个基本特征，并分析其影响。首先，我们展示了由Poisson编码器引入的输入离散化可以在减少时间步数的情况下提高对抗性的鲁棒性。其次，我们通过泄漏集成火（LIF）神经元中泄漏率的增加来量化对抗精度的数量。我们的结果表明，使用LIF神经元和较少时间步长训练的SNN比使用IF（Integrate-Fire）神经元和大量时间步长的SNN更为健壮。通过提出一种从SNN制作攻击的技术，我们克服了在时域中创建基于梯度的对抗输入的瓶颈

 

### PyCARL: A PyNN Interface for Hardware-Software Co-Simulation of Spiking Neural Network

我们介绍了PyCARL，这是一个基于PyNN的通用Python编程接口，用于对尖峰神经网络（SNN）进行硬件-软件协同仿真。通过PyCARL，我们做出了以下两个关键贡献。首先，我们提供PyNN与CARLsim的接口，CARLsim是一种计算效率高，GPU加速且具有生物物理细节的SNN模拟器。 PyCARL促进了CARLsim和PyNN用户之间机器学习模型和代码共享的联合开发，从而促进了一个集成的，更大的神经形态社区。其次，我们在PyCARL中集成了最新的神经形态硬件（例如TrueNorth，Loihi和DynapSE）的周期精确模型，以准确地建模延迟在交流神经元之间出现尖峰并降低性能的硬件延迟。 PyCARL允许用户分析和优化其机器学习模型的纯软件仿真和硬件-软件协同仿真之间的性能差异。我们表明，系统设计师还可以在产品开发阶段的早期使用PyCARL进行设计空间探索，从而加快神经形态产品的部署时间。我们使用功能测试，合成SNN和实际应用程序来评估PyCARL的内存使用情况和仿真时间。我们的结果表明，对于大型SNN，与CARLsim相比，PyCARL不会导致任何重大开销。我们还使用PyCARL来分析这些SNN，以了解最新的神经形态硬件，并证明与纯软件仿真相比存在明显的性能差异。 PyCARL允许在模型开发的早期评估并最小化此类差异

 

### An Efficient Software-Hardware Design Framework for Spiking Neural Network Systems

尖刺神经网络（SNN）是模仿大脑自然行为的第三代神经网络（NN）。 通过基于二进制输入/输出的处理，SNN具有更低的复杂度，更高的密度和更低的功耗。 这项工作提出了一个有效的软件-硬件设计框架，用于在硬件中开发SNN系统。 此外，提出了一种基于分组交换通信方法的低成本神经突触核心设计。 评估结果表明，大小为784：1200：1200：10的ANN到SNN转换方法对MNIST的准确度为99％，而无监督的STDP通过重复连接将大小为784：400的STDP存档为89％。 256个神经元和65k突触的设计也以ASIC 45nm技术实现，面积成本为0.205 $ m m ^ 2 $

 

### Learning to Walk: Spike Based Reinforcement Learning for Hexapod Robot Central Pattern Generation

学习走路-即在性能和能量限制下学习运动仍然是有腿机器人的一项挑战。已针对双足动物，四足动物和六足动物探索了随机梯度，深度强化学习（RL）等方法。这些技术是计算密集型的，并且对于边缘应用通常是禁止的。这些方法依赖于复杂的传感器和数据的预处理，这进一步增加了能量和等待时间。由于神经稀疏发射，尖峰神经网络（SNN）的最新进展有望显着减少计算，并且已显示出将强化学习机制与生物学观察到的尖峰时间相关可塑性（STDP）集成在一起。但是，尚未显示通过学习SNN框架中的中央模式生成器（CPG）的同步模式来训练有腿机器人行走。这可以将SNN的效率与基于CPG的系统的同步运动结合起来，从而在移动机器人技术中提供突破性的端到端学习。在本文中，我们提出了一种基于增强的随机权重更新技术，用于训练峰值CPG。整个系统在带有集成传感器的轻型树莓派平台上实现，从而开辟了令人兴奋的新可能性

 

 

## 2020.2.25~3.13

### Improving STDP-based Visual Feature Learning with Whitening

近年来，尖峰神经网络（SNN）替代了深度神经网络（DNN）。 SNN使用低功率神经形态硬件表现出更高的计算效率，并且使用局部和无监督学习规则（如依赖于时序的可塑性（STDP））进行训练所需的标记数据更少。 SNN已证明其在简单数据集（例如MNIST）的图像分类中的有效性。然而，为了处理自然图像，需要预处理步骤。高斯差（DoG）过滤通常与中心/中心偏编码一起使用，但是会导致信息丢失，这对分类性能不利。在本文中，我们建议在使用STDP学习功能之前将美白用作预处理步骤。在CIFAR-10上进行的实验表明，通过白化，STDP可以学习与标准神经网络更接近的视觉特征，并且与DoG过滤相比，分类性能显着提高。我们还提出了将白化作为卷积内核的一种近似方法，该方法在计算上学起来较便宜，并且更适合在神经形态硬件上实现。在CIFAR-10上进行的实验表明，它的效果与常规美白效果相似。在CIFAR-10和STL-10上进行的跨数据集实验还表明，它在数据集之间相当稳定，从而有可能学习单个增白变换来处理不同的数据集

 

### Temporal Spike Sequence Learning via Backpropagation for Deep Spiking Neural Networks

尖峰神经网络（SNN）非常适合时空学习和在节能型事件驱动神经形态处理器上的实现。但是，与传统人工神经网络的BP方法相比，现有的SNN错误反向传播（BP）跟踪方法缺乏对尖峰不连续点的正确处理，并且性能低下。另外，SNN通常需要大量的时间步才能达到良好的性能，从而导致高延迟，并使基于尖峰的计算无法扩展到深层架构。我们提出了一种新颖的时间尖峰序列学习反向传播（TSSL-BP）方法，用于训练深度SNN，该方法可以分解跨神经元间和内部神经元依赖的两种类型的错误反向传播。它考虑了发射活动的全有或全无特征，通过突触前发射时间捕获神经元间依赖性，以及通过时间捕获神经元内依赖性来捕获每个神经元状态的内部演化。对于各种图像分类数据集，TSSL-BP在几个步骤的短时间窗口内有效地训练了深度SNN，具有改进的准确性和运行时效率，包括比以前报道的CIFAR10的SNN工作提高了2％以上的准确性

### A Deep Unsupervised Feature Learning Spiking Neural Network with Binarized Classification Layers for EMNIST Classification

最终用户AI在大型服务器场上接受了从用户收集的数据的培训。 随着对物联网设备的不断增长的需求，需要能够以节能方式（在边缘）实施的深度学习方法。 在这项工作中，我们使用尖峰神经网络来解决这个问题。 使用二进制激活的依赖于尖峰时序的可塑性（STDP）的无监督学习技术用于从尖峰输入数据中提取特征。 梯度下降（反向传播）仅在输出层上使用以执行分类训练。 平衡的EMNIST数据集获得的精度与其他方法相比具有优势。 还探讨了随机梯度下降（SGD）近似对我们网络学习能力的影响。

### On robot compliance. A cerebellar control approach

本文介绍的工作是一种新颖的生物方法，用于实时（RT）顺应性地控制机械臂。我们在执行扭矩驱动控制的反馈控制回路的核心处集成了尖峰小脑网络。尖刺小脑控制器提供扭矩命令，可进行精确且协调的手臂运动。为了计算这些输出电动机命令，尖刺小脑控制器接收机器人的感觉信号，机器人的目标行为和指示性信号。这些输入信号被转换为在每个时间点唯一表示特定系统状态的一组不断变化的尖峰模式。然后，支持依赖于尖峰时序的可塑性（STDP），从而实现自适应控制。当部署STDP时，尖峰小脑控制器会根据经验不断调整提供给机器人的扭矩命令。反过来，自适应扭矩命令可帮助尖峰的小脑控制器处理模仿人类肌肉（固有弹性）的机器人执行器中的内置弹性元件。我们建议将基于小脑的生物启发控制方案与兼容的机器人自然集成。我们证明，在用于解决小脑运动行为的一系列任务中，我们的合规方法优于默认的工厂安装位置控制的准确性：在平稳运动，快速弹道运动和非结构化场景合规运动中控制六个自由度（DoF）

 

### Bifurcation Spiking Neural Network

尖峰神经网络（SNN）由于其对时变信号进行建模的巨大潜力而备受关注。尖峰神经元的发射速率由预先手动确定的控制速率决定，因此，发射速率是否足以模拟实际的时间序列取决于运气。尽管要求具有自适应的控制速率，但这是一项艰巨的任务，因为在训练过程中学习到的控制速率和连接权重通常会纠缠在一起。在本文中，我们证明了点火速率与峰值生成函数的特征值有关。受到这种见识的启发，通过使尖峰生成功能具有适应的特征值而不是参数控制速率，我们开发了分叉尖峰神经网络（BSNN），该网络具有自适应的发射速率并且对控制速率的设置不敏感。实验验证了BSNN在各种任务上的有效性，表明BSNN的性能优于现有SNN，并且对控制率的设置具有鲁棒性

### Is my Neural Network Neuromorphic? Taxonomy, Recent Trends and Future Directions in Neuromorphic Engineering

在本文中，我们回顾了最近3年在Neuromorphic工程学框架下发布的最新工作，以分析此类系统之间的共同特征。我们看到没有明确的共识，但是每个系统都具有以下一项或多项功能：（1）模拟计算（2）非vonNeumann体系结构和低精度数字处理（3）尖峰神经网络（SNN），其组件紧密相关生物学。我们比较了最近的机器学习加速器芯片，以显示模拟处理和降低的位精度架构确实具有最佳的吞吐量，能量和面积效率。但是，仅采用非von-Neumann体系结构，纯数字体系结构也可以实现相当高的效率。有了用于数字硬件设计的设计自动化工具，它就对工业设计在不久的将来采用模拟处理的可能性提出了疑问。接下来，我们讨论了为神经形态系统设计的进展定义标准并选择适当的基准的重要性，并提出了此类基准的一些所需特性。最后，我们将脑机接口显示为满足此类基准的所有标准的潜在任务

### Explicitly Trained Spiking Sparsity in Spiking Neural Networks with Backpropagation

人们正在研究尖峰神经网络（SNN）的潜在能量效率，这种能量效率是由事件驱动的稀疏计算引起的。许多新近的工作已经证明了通过深化不连续神经元尖峰或触发事件的梯度，可以有效地实现深尖峰神经网络（SNN）的反向传播。这些替代梯度尖峰反向传播算法的一个有益副作用是，现在可以直接在梯度计算中直接考虑触发额外计算的尖峰。我们建议在损失函数中明确包含尖峰计数以及传统的误差损失，从而使反向传播学习算法针对权重参数和尖峰稀疏度优化权重参数。在现有的超参数化神经网络理论的支持下，存在许多具有有效等效精度的解状态。这样，在此多目标优化过程中的训练过程中，对两个损失目标的适当加权可以提高尖峰稀疏性，而不会显着降低准确性。我们还探索了一种模拟的退火启发式损失加权技术，以随着训练时间的增加而增加稀疏性的加权。我们在Cifar-10数据集上的初步结果显示，与仅针对准确性进行训练的同等SNN相比，具有等精度的峰值活动降低了70.1％，如果允许折衷降低1％，则峰值活动降低了73.3％。在分类准确性上

### Reinforcement co-Learning of Deep and Spiking Neural Networks for Energy-Efficient Mapless Navigation with Neuromorphic Hardware

节能无地图导航对于移动机器人来说至关重要，因为它们会在机载资源有限的情况下探索未知环境。尽管最近的深度强化学习（DRL）方法已成功应用于导航，但其高能耗限制了其在许多机器人应用中的使用。在这里，我们提出了一种神经形态方法，将尖峰神经网络的能量效率与DRL的最优性相结合，以学习无地图导航的控制策略。我们的混合框架“尖峰深度确定性策略梯度（SDDPG）”由尖峰参与者网络（SAN）和深度评论者网络组成，其中两个网络使用梯度下降共同训练。经过培训的SAN已部署在英特尔的Loihi神经形态处理器上。共同学习使两个网络之间能够进行协同信息交换，从而使它们可以通过共享表示学习来克服彼此的局限性。当在模拟和真实世界的复杂环境中进行验证时，我们在Loihi上的方法不仅每次推理所消耗的能量比Jetson TX2上的DDPG少75倍，而且成功导航到目标的概率更高，范围为1 \ ％至4.2 \％，具体取决于前向传播时间步长。这些结果加强了我们正在进行的努力，以设计灵感来自大脑的算法来控制具有神经形态硬件的自主机器人。

### RMP-SNNs: Residual Membrane Potential Neuron for Enabling Deeper High-Accuracy and Low-Latency Spiking Neural Networks

随着第三代人工神经网络可以实现低功耗事件驱动的数据分析，尖峰神经网络（SNN）最近引起了广泛的研究兴趣。通过将经过训练的模拟神经网络（ANN）（包括整流线性单位（ReLU））转换为由具有“适当”触发阈值的集成并发射神经元组成的SNN，可以获得用于图像识别任务的性能最佳的SNN。与原始ANN相比，转换后的SNN通常会导致准确性损失，并且需要大量的推理时间步才能达到最佳准确性。我们发现，转换后的SNN的性能下降源于使用“硬重置”尖刺神经元，一旦其膜电位超过触发阈值，该神经元就会驱动到固定的重置电位，从而导致SNN推理期间的信息丢失。我们提出使用“软重置”尖峰神经元模型（称为残留膜电位（RMP）尖峰神经元）进行ANN-SNN转换，该模型在点火瞬间将“残留”膜电位保持在阈值以上。我们在具有挑战性的数据集（包括CIFAR-10（93.63％top-1），CIFAR-100（70.928％top--）中使用具有RMP神经元的VGG-16，ResNet-20和ResNet-34 SNN演示了近乎无损的ANN-SNN转换。 1）和ImageNet（73.26％top-1精度）。我们的结果还表明，RMP-SNN的精度与转换后的SNN具有“硬重置”峰值神经元所提供的精度相当，而整个数据集的推理时间却减少了2-8倍

 

### Event-Based Angular Velocity Regression with Spiking Networks

尖峰神经网络（SNN）是受生物启发的网络，可处理作为时间尖峰而不是数值传送的信息。只要在短时间内出现大量尖峰，SNN的尖峰神经元只会产生尖峰。由于其基于尖峰的计算模型，与标准的人工神经网络不同，SNN可以处理来自基于事件的异步传感器的输出，而无需任何预处理，而且功耗极低。由于专用的神经形态硬件在硅中实现了高度可并行化的SNN概念，因此这是可能的。然而，SNN没有像人工神经网络那样受欢迎。这不仅源于其输入格式相当不常规的事实，还源于训练尖峰网络的挑战。尽管它们具有时间性和最近的算法进步，但它们大多已针对分类问题进行了评估。我们首次提出给定事件相机的事件数值的时间回归问题。我们专门研究了带有SNN的旋转事件摄像机的3-DOF角速度的预测。直接从不规则的，基于事件的异步输入直接连续地对角速度进行预测是造成此问题的困难。直接使用事件摄像机的输出而无需任何预处理，可确保我们继承它们提供的超过传统摄像机的所有优势。那就是高时间分辨率，高动态范围和没有运动模糊。为了评估SNN在此任务上的性能，我们引入了从真实全景图像生成的合成事件相机数据集，并表明我们可以成功训练SNN以执行角速度回归

### S4NN: temporal backpropagation for spiking neural networks with one spike per neuron

我们为多层尖峰神经网络（SNN）提出了一种新的监督学习规则，该规则使用一种称为时间顺序编码的时间编码形式。通过这种编码方案，所有神经元每个刺激都会精确发射一个尖峰，但是激发顺序会携带信息。特别地，在读出层中，要发射的第一个神经元确定刺激的类别。我们针对此类网络推导了一种新的学习规则，称为S4NN，类似于传统的错误反向传播，但基于延迟。我们展示了如何在具有任意层数的前馈网络中向后计算近似误差梯度。这种方法通过受监督的多层全连接层SNN达到了最先进的性能：MNIST数据集的测试准确性为97.4％，Caltech Face / Motorbike数据集的测试准确性为99.2％。但是，我们使用的神经元模型（非泄漏集成和发射）比以前所有工作中使用的模型都简单得多。提议的S4NN的源代码可从https://github.com/SRKH/S4NN公开获得

### Minimal spiking neuron for solving multi-label classification tasks

Multi-Spike Tempotron（MST）是一个功能强大的单脉冲神经元模型，可以解决复杂的监督分类任务。尽管功能强大，但它内部也很复杂，评估起来计算量很大，并且不适合神经形态硬件。在这里，我们旨在了解是否有可能简化MST模型，同时保留其学习和处理信息的能力。为此，我们引入了一系列通用神经元模型（GNM），它们是Spike Response模型的特例，并且比MST更为简单和便宜。我们发现，在广泛的参数范围内，GNM至少可以像MST一样学习。我们将膜电位的时间自相关确定为GNM的最重要成分，这使其能够对多个时空模式进行分类。我们还将GNM解释为一个化学系统，因此在概念上将神经网络与分子信息处理的计算联系起来。我们通过为GNM提出其他训练方法（包括错误跟踪学习和错误反向传播）来结束本文

 

### Exploiting Neuron and Synapse Filter Dynamics in Spatial Temporal Learning of Deep Spiking Neural Network

最近发现的生物启发式神经网络（SNN）的时空信息处理能力已经实现了一些有趣的模型和应用。然而，由于缺乏健壮的训练算法，设计大规模和高性能模型仍然是一个挑战。具有时空特性的生物似然SNN模型是一个复杂的动态系统。每个突触和神经元表现为能够保留时间信息的过滤器。由于现有训练算法中忽略了这种神经元动力学和滤波器效果，因此SNN降级为无记忆系统，并失去了时间信号处理能力。此外，尖峰定时在信息表示中起着重要作用，但是传统的基于速率的尖峰编码模型仅统计地考虑尖峰序列，并丢弃其时间结构所携带的信息。为了解决上述问题，并利用SNN的时间动态，我们将SNN公式化为具有神经元非线性的无限冲激响应（IIR）滤波器网络。我们提出了一种训练算法，该算法能够通过搜索最佳的突触滤波器内核和权重来学习时空模式。所提出的模型和训练算法被用于构建包括MNIST，NMNIST，DVS 128等在内的综合和公共数据集的关联记忆和分类器；其准确性优于最新方法

### Indirect and Direct Training of Spiking Neural Networks for End-to-End Control of a Lane-Keeping Vehicle

基于生物突触可塑性构建尖峰神经网络（SNN）在完成快速且节能的计算方面具有广阔的发展潜力，这对移动机器人应用非常有益。然而，由于缺乏实用的训练方法，SNN在机器人领域的实现受到限制。因此，在本文中，我们介绍了用于车道保持车辆的SNN的间接和直接端到端训练方法。首先，我们采用通过\ textcolor {black} {Deep Q-Learning}（DQN）算法学习到的策略，然后使用监督学习将其传输到SNN。其次，我们采用奖励调制的依赖尖峰时序的可塑性（R-STDP）直接训练SNN，因为它结合了强化学习和众所周知的尖峰时序的可塑性（STDP）的优点。我们在三种情况下检查了提出的方法，在这种情况下，通过使用基于事件的神经形态视觉传感器来控制机器人，使其保持在车道标记内。通过与本文中介绍的其他三种算法进行比较，我们进一步证明了R-STDP方法在横向定位精度和训练时间步长方面的优势

 



## 2020.2.18~2.24

### Effective AER Object Classification Using Segmented Probability-Maximization Learning in Spiking Neural Networks

与传统的基于帧的摄像机相比，地址事件表示（AER）摄像机由于具有高时间分辨率和低功耗的优势，最近引起了更多关注。由于AER摄像机将视觉输入记录为异步离散事件，因此它们固有地适合与尖峰神经网络（SNN）协调，该神经网络在神经形态硬件上具有生物学上的合理性和能源效率。但是，由于缺乏针对这种新表示的有效学习算法，因此使用SNN执行AER对象分类仍然具有挑战性。为了解决这个问题，我们提出了一种使用新颖的分段概率最大化（SPA）学习算法的AER对象分类模型。从技术上讲，1）SPA学习算法迭代地最大化样本所属类的概率，以提高神经元响应的可靠性和学习的有效性； 2）在SPA中引入了峰值检测（PD）机制，以逐段地定位信息时间点，基于此机制，整个事件流中的信息可以被学习充分利用。大量的实验结果表明，与最新方法相比，我们的模型不仅更有效，而且需要较少的信息才能达到一定的准确性。

## 2020.1.16~2.17

### A Supervised Learning Algorithm for Multilayer Spiking Neural Networks Based on Temporal Coding Toward Energy-Efficient VLSI Processor Design

尖峰神经网络（SNN）是受大脑启发的数学模型，具有以尖峰形式处理信息的能力。当在VLSI电路中实现时，SNN不仅将提供新的机器学习算法，而且还将提供节能的计算模型。在本文中，我们提出了一种新的基于时间编码的SNN监督学习算法。设计该算法中的尖峰神经元，以促进具有模拟电阻式存储器的模拟VLSI实现，从而可以实现超高的能源效率。我们还提出了几种技术来提高识别任务的性能，并表明所提出算法的分类精度与MNIST数据集上最新的时间编码SNN算法的分类精度一样高。最后，我们讨论了所提出的SNN的鲁棒性，以抵抗由器件制造过程引起的变化，这在模拟VLSI实现中是不可避免的。我们还提出了一种抑制制造过程中的变化对识别性能的影响的技术。

### Spiking Neural Predictive Coding for Continual Learning from Data Streams

为了在专用神经形态硬件中进行节能计算，我们提出了“尖峰神经编码网络”，这是由预测编码理论强烈推动的一系列人工神经模型的实例。本质上，该模型通过无休止的“猜测和检查”过程来工作，其中神经元相互预测彼此的活动值，然后立即调整其自身的活动以做出更好的未来预测。我们的神经系统的交互性，迭代性非常适合数据感觉流预测的连续时间公式，并且正如我们所展示的，该模型的结构产生了一个简单的局部突触更新规则，可用于补充或替换在线峰值-时间依赖性可塑性。在本文中，我们将对包含泄漏的集成点火装置的模型实例化进行试验。但是，我们的模型所处的总体框架自然可以包含更复杂的形式化神经元，例如霍奇金-赫克斯利模型。我们在模式识别中的实验结果证明了当二元尖峰序列是神经元间通信的主要范例时，所提出模型的潜力。值得注意的是，我们的模型在分类性能方面具有竞争力，可以进行在线半监督学习，从一系列任务中进行学习时自然会减少遗忘，并且比流行的人工神经网络在计算上更经济并且在生物学上更合理

### A Large Scale Event-based Detection Dataset for Automotive

我们介绍了第一个非常大的事件摄像机检测数据集。 该数据集由使用304x240 GEN1传感器采集的39个小时以上的汽车记录组成。 它包含开放的道路和非常多样的驾驶场景，范围涵盖城市，高速公路，郊区和乡村，以及不同的天气和照明条件。 记录中包含的汽车和行人的手动边框注释也以1至4Hz的频率提供，总共产生了超过255,000个标签。 我们相信，这种大小的标记数据集的可用性将有助于基于事件的视觉任务（例如对象检测和分类）的重大进步。 我们还期望在其他任务中受益，例如光流，运动的结构和跟踪，例如，通过自我监督的学习方法可以利用大量数据。

### Probabilistic spike propagation for FPGA implementation of spiking neural networks

尖峰神经网络的评估需要获取大量的突触权重以更新突触后神经元。 这限制了并行性，并成为硬件的瓶颈。 我们提出了一种基于权重的概率解释的尖峰传播方法，从而减少了内存访问和更新。 我们研究了将随机性引入尖峰处理的影响，并在基准网络上表明可以做到这一点，而对识别精度的影响却很小。 我们针对Xilinx Zynq平台上的MNIST和CIFAR10数据集，介绍了全连接和卷积网络上的体系结构和准确性之间的取舍。

### Temporal Pulses Driven Spiking Neural Network for Fast Object Recognition in Autonomous Driving

长期以来，根据传感数据进行准确的实时物体识别一直是自动驾驶的关键和挑战性任务。尽管深层神经网络（DNN）已成功应用于该领域，但大多数现有方法仍然严重依赖于对LiDAR传感器衍生的脉冲信号的预处理，因此会带来额外的计算开销和相当大的延迟。在本文中，我们提出了一种利用尖峰神经网络（SNN）直接利用原始时间脉冲直接解决对象识别问题的方法。通过对来自LiDAR和动态视觉传感器（DVS）的各种数据集（包括Sim LiDAR，KITTI和DVS-barrel）进行评估，我们提出的方法已显示出与最新方法相当的性能，同时实现了显着的时间效率。它强调了SNN在自动驾驶和相关应用中的巨大潜力。据我们所知，这是首次使用SNN直接对原始时间脉冲执行对象识别的尝试。

### Neural Autopoiesis: Organizing Self-Boundary by Stimulus Avoidance in Biological and Artificial Neural Networks

生命有机体必须积极维护自身才能继续生存。自生是生命生物研究中的一个关键概念，通过系统本身的动态调节，生物的边界不是静态的。为了研究自我边界的自主调节，我们集中在利用生物和人工神经网络对环境变化的神经动力响应上。先前的研究表明，具有尖峰时序依赖性可塑性（STDP）的内在培养神经网络和尖峰神经网络会避免外部刺激，因此会学习一种行为。在本文中，作为我们使用具体化的培养神经元进行实验的结果，我们发现还有第二个属性可以使网络避免刺激：如果代理无法学习避免外部刺激的动作，则趋向于减少刺激-引起尖峰，好像忽略了不可控制的输入。我们还表明，这种行为是通过用不对称STDP掺入神经网络来再现的。我们认为这些性质被视为网络的自我和非自我的自治调节，其中可控神经元被视为自我，不可控神经元被视为非自我。最后，我们通过提出避免刺激的原理来介绍神经自动生成

### An Internal Clock Based Space-time Neural Network for Motion Speed Recognition

在这项工作中，我们提出了一种新颖的基于内部时钟的时空神经网络，用于运动速度识别。开发的系统具有一个尖峰序列编码器，一个带有内部时钟行为的尖峰神经网络（SNN），一个模式转换块和一个网络动态相关可塑性（NDDP）学习块。核心原理是，开发的SNN将自动调整其网络模式频率（内部时钟频率），以识别速度域中的人体运动。我们将卡通和现实世界的视频都用作训练基准，结果表明我们的系统不仅可以识别速度差异很大的运动（例如跑步，走路，跳跃，惊奇（思考）和静止），而且还可以识别速度差异很小的运动例如跑步和快走。推理准确度可高达83.3％（卡通视频）和75％（真实视频）。同时，该系统在学习阶段仅需要六个视频数据集，并进行多达42个培训试验。硬件性能估计表明，训练时间为0.84-4.35s，功耗为33.26-201mW（基于ARM Cortex M4处理器）。因此，我们的系统利用了对小型数据集的需求，快速学习和低功耗性能的独特学习优势，这为基于边缘或可扩展AI的应用程序展示了巨大的潜力。

### Classifying Images with Few Spikes per Neuron

与标准人工神经网络（ANN）相比，尖峰神经网络（SNN）有望为AI实施提供大幅减少的能源预算。除了可以在芯片上进行有效训练的递归SNN模块外，许多AI应用还要求使用前馈卷积神经网络（CNN）作为视觉或其他感官输入的预处理器。标准解决方案是训练通常由整流后的线性ReLU函数作为激活函数的，由非加标神经元组成的CNN，然后通过速率编码将这些带有ReLU神经元的CNN转换为SNN。然而，这产生了具有长等待时间和小吞吐量的SNN，因为神经元必须发出的尖峰数量约为相应CNN门的输出值数量N的数量级，后续各层必须能够区分。我们介绍了一种新的ANN-SNN转换，称为FS转换，为此仅需要记录N个时间步，从信息论的角度来看这是最佳的。这可以通过尖峰神经元模型的简单变化来实现，该变化没有膜泄漏，但是发射阈值呈指数下降。我们显示出，对于基于ImageNet和CIFAR10的图像分类，与基于速率的转换相比，此新转换减少了等待时间并大大提高了吞吐量，同时实现了与ANN几乎相同的分类性能

### Multi-Objective Optimization for Size and Resilience of Spiking Neural Networks

受大脑中连接机制的启发，神经形态计算体系结构在硅中模拟了尖峰神经网络（SNN）。这样，神经形态架构的设计和开发的目标是拥有可以执行控制和机器学习任务的小型，低功耗芯片。但是，开发的硬件的功耗可能极大地取决于芯片上正在评估的网络的大小。此外，在芯片上评估的经过训练的SNN的准确性可能会因硬件中的电压和电流变化而变化，从而扰乱网络的学习权重。尽管在硬件方面已尽力将这些干扰降到最低，但基于软件的策略可使部署的网络更具弹性，可以帮助进一步缓解该问题。在这项工作中，我们研究了两种神经形态架构实现中的尖刺神经网络，目的是减小它们的大小，同时提高它们对硬件故障的适应性。我们利用一种进化算法来训练SNN，并提出一个多目标适应度函数来优化SNN的大小和弹性。我们证明了该策略可导致性能更好的小型网络，对硬件故障具有更大的弹性。

### Synaptic Integration of Spatiotemporal Features with a Dynamic Neuromorphic Processor

尖峰神经元可以通过突触前尖峰模式的非线性突触和树突状整合来执行时空特征检测。非线性树突的多室模型和相关的神经形态电路设计能够忠实地模仿这种动态集成过程，但是这些方法还与较高的计算成本或电路规模相关。在这里，我们研究了时空尖峰模式与DYNAP-SE神经形态处理器中点神经元上的多个动态突触的突触整合，这可以提供一种互补的资源高效，灵活性较差的特征检测方法。我们研究了如何将先前提出的动态突触的兴奋性-抑制性对组合在一起以整合多个输入，并且将这一概念推广到一个抑制性突触与多个兴奋性突触结合的情况。我们通过测量和分析神经形态神经元回路的膜电位来表征延迟的兴奋性突触后突触电位（EPSPs）。我们发现，由于设备失配，可以通过选择不同的突触组合以拟议的方式实现生物学相关的EPSP延迟，每个神经元的变化幅度为10毫秒。基于这些结果，我们证明了在DYNAP-SE中具有动态突触的单点神经元，可以选择性地响应具有特定时空结构的突触前突波，例如，可以对单个神经元进行视觉特征调整。

### Asynchronous Tracking-by-Detection on Adaptive Time Surfaces for Event-based Object Tracking

作为异步生物灵感视觉传感器的事件摄像机在各种情况下都显示出了巨大的潜力，例如快速运动和低照度场景。但是，大多数基于事件的对象跟踪方法都是针对具有未纹理对象和背景整齐的场景而设计的。支持基于边界框的对象跟踪的基于事件的对象跟踪方法很少。这项工作的主要思想是为基于通用包围盒的对象跟踪提出一种基于事件的异步跟踪（ETD）方法。为了实现此目标，我们提出了一种线性时间衰减的自适应时间表面（ATSLTD）事件到帧转换算法，该算法将异步视网膜事件的时空信息异步有效地扭曲到具有清晰对象的一系列ATSLTD帧中轮廓。我们将ATSLTD帧的序列馈送到所提出的ETD方法，以执行准确而有效的对象跟踪，从而充分利用了事件摄像机的高时间分辨率特性。我们将提出的ETD方法与基于常规相机或事件相机的7种流行的对象跟踪方法以及ETD的两种变体进行了比较。实验结果表明，所提出的ETD方法在处理各种挑战性环境中具有优势。

### End-to-end Learning of Object Motion Estimation from Retinal Events for Event-based Object Tracking

事件照相机是异步生物启发式视觉传感器，在计算机视觉和人工智能中显示出巨大潜力。但是，将事件摄像机应用于对象级运动估计或跟踪仍处于起步阶段。这项工作背后的主要思想是提出一种新颖的深度神经网络，以学习和回归用于基于事件的对象跟踪的参数对象级运动/变换模型。为实现此目标，我们提出了一种具有线性时间衰减的同步时间表面（TSLTD）表示，该表示将异步视网膜事件的时空信息有效编码为具有清晰运动模式的TSLTD帧。我们将TSLTD帧的序列馈送到一个新颖的视网膜运动回归网络（RMRNet），以执行端到端的5自由度对象运动回归。我们的方法与基于常规摄像机或事件摄像机的最新对象跟踪方法进行了比较。实验结果表明，我们的方法在处理各种挑战性环境（如快速运动和低照度条件）方面具有优势。

 

### Spiking Inception Module for Multi-layer Unsupervised Spiking Neural Networks

IJCNN 2020

作为大脑灵感的方法，尖刺神经网络（Spineing Neural Network，SNN）由于具有生产超高能效硬件的潜力而备受关注。基于峰值计时依赖可塑性（STDP）的竞争性学习是一种训练无监督SNN的流行方法。但是，以前通过这种方法训练的无监督SNN仅限于只有一个可学习层的浅层网络，与多层SNN相比，无法获得令人满意的结果。在本文中，我们通过以下方法缓解了这一限制：1）受人工神经网络（ANN）文献中的Inception模块启发，我们提出了Spike Inception（Sp-Inception）模块。该模块通过基于STDP的竞争性学习进行培训，在学习能力，学习效率和健壮性方面均优于基准模块； 2）我们建议使用Pooling-Reshape-Activate（PRA）层来使Sp-Inception模块可堆叠； 3）我们堆叠了多个Sp-Inception模块，以构建多层SNN。我们的方法大大超过了图像分类任务的基线方法，并在现有的无监督SNN中达到了MNIST数据集上的最新结果。

## 



## 2020.1.7~15

### Exploring Adversarial Attack in Spiking Neural Networks with Spike-Compatible Gradient

最近，通过时间启发式学习算法进行的反向传播已广泛引入SNN，以提高性能，这为在时空梯度图的情况下准确攻击模型提供了可能性。我们提出了两种方法来解决梯度输入不兼容和梯度消失的挑战。具体来说，我们设计了一个梯度到尖峰转换器，将连续的梯度转换为与尖峰输入兼容的三元梯度。然后，我们设计一个梯度触发器来构造三元梯度，当满足所有零梯度时，它们可以以可控的周转率随机翻转尖峰输入。将这些方法放在一起，我们为由监督算法训练的SNN建立对抗性攻击方法。此外，我们分析了训练损失函数和倒数第二层的发射阈值的影响，这表明交叉熵损失下的“陷阱”区域可以通过阈值调整来逃避。进行了广泛的实验以验证我们解决方案的有效性。除了对影响因素进行定量分析外，我们证明SNN比ANN更能抵抗对抗攻击。这项工作可以帮助揭示在SNN攻击中发生的情况，并可能刺激对SNN模型和神经形态设备的安全性进行更多的研究。

### BioSNet: A Fast-Learning and High-Robustness Unsupervised Biomimetic Spiking Neural Network

刺神经网络（Spiking Neural Network，SNN）作为一种受大脑启发的机器学习算法，与人工神经网络（ANN）相比，它更接近人脑的计算机制，更适合揭示智能的本质，近年来受到越来越多的关注年份。另外，SNN处理的信息采用离散尖峰的形式，这使SNN具有低功耗特性。在本文中，我们提出了一种高效且强大的无监督SNN，名为BioSNet，具有很高的生物学可信度，可以处理图像分类任务。在BioSNet中，我们提出了一种新的仿生加标神经元模型，称为MRON，该模型受人脑中“识别记忆”的启发，还设计了一种与人脑生物学特性相对应的有效而强大的网络架构，并将传统的投票机制扩展到了全民投票（VFA）解码层，以减少解码期间的信息丢失。仿真结果表明，BioSNet不仅可以在MNIST / EMNIST数据集上实现最新的无监督分类精度，而且还具有出色的学习效率和很高的鲁棒性。具体来说，每个类别仅训练几十个样本的BioSNet可以获得超过80％的良好分类精度，并且随机删除BioSNet中甚至95％的突触或神经元只会导致轻微的性能下降。

### Recognizing Images with at most one Spike per Neuron

为了将经过训练的人工神经网络（ANN）的性能移植到尖峰神经网络（SNN）（可以在神经形态硬件中以大大降低的能耗实现），需要高效的ANN到SNN转换。先前的转换方案着重于通过尖峰神经元的激发速率在ANN中表示整流线性（ReLU）门的模拟输出。但这对于其他常用的ANN门来说是不可能的，甚至对于ReLU门也降低了吞吐量。我们介绍了一种新的转换方法，其中，ANN中的门几乎可以是任何类型的门，都由一小串尖刺神经元电路模拟，每个神经元最多有一个尖峰（AMOS）。我们表明，这种AMOS转换将ImageNet的SNN的准确性从74.60％提高到80.97％，从而使其达到最佳可用ANN准确性（85.0％）。 SNN的Top5准确性提高到95.82％，甚至更接近于ANN的97.2％的最佳Top5性能。此外，AMOS转换将基于尖峰的图像分类的延迟和吞吐量提高了几个数量级。因此，这些结果表明，SNN为开发将高性能与应用程序的多功能性相结合的AI的高能效硬件提供了可行的方向。

（mark:转换）

### Direct training based spiking convolutional neural networks for object recognition

最近，基于直接训练的尖峰神经网络（SNN）由于其在新兴的神经形态硬件上的高能源效率而备受关注。但是，由于加标活动的不可区分性，大多数相关的SNN对于复杂的数据集（如CIFAR-10）仍然无法实现较高的目标识别精度。即使其中一些可以达到90％的精度，这些网络中的能耗仍然很高。考虑到这一点，我们在本研究中提出了一种使用时间编码方案的基于直接监督学习的尖峰卷积神经网络（SCNN），旨在利用最小可训练参数来高精度识别图像中的对象。 MNIST和CIFAR-10数据集用于评估建议网络的性能。对于MNIST数据集，与其他最新模型相比，拟议的带噪声输入的网络能够达到较高的识别准确度（99.13％），但使用的可训练参数要少得多。对于CIFAR-10数据集，所提出的带有数据增强步骤的网络可以达到80.49％的识别精度，这是在使用时域编码方式的直接训练基于SNN的领域中最新的高精度。另外，在此类网络中使用的可训练参数的数量远少于文献中报道的基于转换的SCNN中的数量。

### Event-based Moving Object Detection and Tracking

基于事件的视觉传感器，例如动态视觉传感器（DVS），非常适合实时运动分析。这种传感器的读数中包含的独特属性提供了高时间分辨率，对光的出色灵敏度和低延迟。这些特性为在最复杂的情况下有效且可靠地估计运动提供了依据，但是这些优点是有代价的，基于事件的现代视觉传感器分辨率极低，会产生大量噪声，因此需要开发新颖的算法来处理异步事件流。本文提出了一种新的，高效的异步相机目标跟踪方法。我们提出一种新颖的事件流表示形式，使我们能够利用有关事件流的动态（时间）组成部分的信息。使用参数模型对事件流的3D几何进行近似，以对摄像机进行运动补偿（无需特征跟踪或显式的光流计算），然后在迭代过程中检测出不符合模型的运动对象。我们演示了关于独立运动检测和跟踪任务的框架，其中我们使用时间模型不一致来在极快运动的挑战性情况下定位不同运动的对象。

## 

## 2020.1.1~6

### Versatile emulation of spiking neural networks on an accelerated neuromorphic substrate

我们提出了基于模拟神经突触核心并通过嵌入式微处理器增强的用于复杂可塑性和实验控制的新型BrainScaleS-2神经形态结构的第一个实验结果。 与生物动力学相比，其高的加速因子为1000，通过允许快速模拟长期实验或在许多连续试验中进行快速迭代，可以执行昂贵的计算任务。 我们的体系结构的灵活性在一组五个不同的实验中得到了证明，这些实验着重于BrainScaleS-2系统的不同方面。



## 2019.12.23~31

### Ultra Low-Power and Real-time ECG Classification Based on STDP and R-STDP Neural Networks for Wearable Devices

本文提出了一种用于超低功耗可穿戴设备的实时心脏监护的新型ECG分类算法。 所提出的解决方案基于尖峰神经网络，这是神经网络的第三代。 具体来说，我们采用了依赖于尖峰时序的可塑性（STDP）和奖励调制的STDP（R-STDP），其中模型权重是根据尖峰信号以及奖励或惩罚信号的时间进行训练的。 实验表明，所提出的解决方案适合于实时操作，与以前的方法相比具有可比的精度，更重要的是，其能量消耗明显小于以前的基于神经网络的解决方案。

### An uncertainty principle for neural coding: Conjugate representations of position and velocity are mapped onto firing rates and co-firing rates of neural spike trains

海马系统包含神经种群，这些种群编码动物在空间中导航时的位置和速度。在这里，我们表明，这些种群可以在其峰值序列中嵌入两个代码：通过单元内峰值间隔传达的发火率代码（R）和通过单元之间峰值间隔传达的共发率代码（R'）。这两个代码的行为互为共轭，服从物理上的不确定性原理的模拟：R中传递的信息以R'中的信息为代价，反之亦然。当尖峰序列编码一对共轭变量（例如位置和速度）时，这种权衡例外会发生，它们不会竞争R和R'的容量。为了说明这一点，我们描述了两种用于解码R和R'的生物学启发方法，分别称为sigma和sigma-chi解码。头部方向（HD）和网格单元的仿真显示，如果针对位置（而非速度）调整了发射速率，则通过sigma解码恢复位置，而通过sigma-chi解码恢复速度。相反，对经过θ调制的“速度单元”之间的振荡干扰的仿真表明，如果针对位置（而不是速度）调整了同火率，则可以通过sigma-chi解码恢复位置，而通过sigma解码恢复速度。在这两个极端之间，有关两个变量的信息可以分布在两个通道上，并且可以由两个解码器部分恢复。这些结果表明，具有不同时空调整特性的神经元（例如速度与网格细胞）可能不会编码不同的信息，而是会在R和R'上以不同的方式分配有关位置和速度的类似信息

 

### Fast and deep neuromorphic learning with time-to-first-spike coding

对于在环境压力下运行的生物制剂而言，能耗和反应时间至关重要。类似地，工程系统还致力于缩短解决时间和降低能量解决方案的特性。在神经元实施的水平上，这意味着以尽可能少的和尽可能早的峰值实现期望的结果。在“初学者时间编码”框架中，这两个目标都是学习固有的新兴特征。在这里，我们描述了针对泄漏集成和发射神经元的分层网络的基于错误反向传播的学习的严格推导。我们通过结合具有有限时间常数的动力学并优化相对于底物可变性的反向传递，明确解决了与生物学上的合理性和对神经形态底物的适用性相关的两个问题。这缩小了以前的第一次学习时间模型与生物神经元动力学模型之间的差距，从而还可以对从它们的生物原型继承这些动力学的模拟神经形态设备进行快速而节能的推断，我们在两代BrainScaleS上进行了演示模拟神经形态结构。

### Structural plasticity on an accelerated analog neuromorphic hardware system

在计算神经科学以及机器学习中，神经形态设备有望成为神经网络仿真的加速且可扩展的替代方案。 它们的神经连通性和突触能力取决于其特定的设计选择，但始终受到内在的限制。 在这里，我们提出一种策略，通过不断地重新布线突触前和突触后伙伴，同时保持神经元扇入恒定和连接组稀疏，来在这些约束条件下优化资源分配。 在我们的实现中，该算法是在定制的嵌入式数字处理器上执行的，该处理器与由尖峰神经元和突触电路组成的混合信号基质配合使用。 我们在一个简单的有监督的学习场景中评估了我们提出的算法，显示了其针对训练数据的性质以及整体计算效率来优化网络拓扑的能力。

## 

## 2019.12.13~22

### Network of Evolvable Neural Units: Evolving to Learn at a Synaptic Level

尽管近年来，通过整体架构和优化策略的各种变化，深度神经网络取得了巨大的成功，但其基本的基础设计在很大程度上保持不变。另一方面，计算神经科学为神经处理机制提供了生物学上更现实的模型，但是它们仍然是对实际实验观察到的行为的高级抽象。在这里提出了一个模型，该模型将神经科学，机器学习和进化算法联系起来，以可扩展的方式进化神经元的个体躯体和突触隔室模型。与其尝试手动为所有在神经处理过程中观察到的复杂性和多样性推导模型，我们提出了一种可进化神经单元（ENU），它可以近似每个神经元和突触的功能。我们证明，这种类型的单位可以演化为模仿整合和射击神经元和突触时标依赖可塑性。此外，通过构建一种新型的神经网络，其中每个突触和神经元都是这样一个可进化的神经单元，我们证明有可能发展出一种能够学习解决T迷宫环境任务的智能体。该网络独立发现尖峰的动力学和强化型学习规则，从而开辟了一条新途径，朝着受到生物启发的人工智能发展。

### Faster and Simpler SNN Simulation with Work Queues

我们提供了一种时钟驱动的Spiking神经网络模拟器，其速度比现有技术快3倍，而同时，它更通用，并且在用户和维护者方面都需要较少的编程工作。 通过围绕“工作队列”设计我们的管道使之成为可能，“工作队列”充当阶段之间的接口，并大大降低了实现的复杂性。 我们使用一系列基准上的三个成熟的SNN模型来评估我们的工作。

### Deep SCNN-based Real-time Object Detection for Self-driving Vehicles Using LiDAR Temporal Data

实时准确检测三维（3D）对象是自动驾驶汽车的基本必要条件。传统的计算机视觉方法基于卷积神经网络（CNN）。尽管在KITTI视觉基准数据集上使用CNN的准确性已取得了巨大的成功，但很少有相关研究检查其能耗需求。尖刺神经网络（SNN）和尖刺CNN（SCNN）的能耗率低于CNN。但是，很少有研究使用SNN或SCNN来检测物体。因此，我们开发了一种新颖的数据预处理层，该层将3D点云的尖峰时间转换为输入，并在YOLOv2架构上使用SCNN通过尖峰信号检测对象。此外，我们提出了一种能耗和网络稀疏性的估算方法。结果表明，所建议的网络在NVIDIA GTX 1080i图形处理单元上以35.7 fps的更高帧速率运行。此外，建议的具有跳过连接的网络比没有跳过连接的网络表现出更好的性能。两者均在KITTI数据集上达到了最新的检测精度，并且我们的网络平均消耗了0.585 mJ（低）能量，平均稀疏度为56.24％。

### Learning spatiotemporal signals using a recurrent spiking network that discretizes time

学习产生时空序列是大脑必须解决的常见任务。大脑可以使用相同的神经底物来产生不同的顺序行为。大脑学习和编码此类任务的方式仍然未知，因为当前的计算模型通常不使用现实的生物学上可行的学习方法。在这里，我们提出了一个模型，其中由兴奋性和抑制性生物物理神经元组成的尖峰递归网络驱动一个读出层：训练该驱动器递归网络的动力学以对时间进行编码，然后将其映射通过读出的神经元来编码另一个维度。 ，例如空间或相位。可以通过突触权重来学习不同的时空模式，并将其编码为遵循常见Hebbian学习规则的读出神经元。我们证明了该模型能够在行为相关的时间尺度上学习时空动态，并且我们证明了所学习的序列在自发活动过程中得到了强大的重放。



## 2019.12.7~12

### A Neural Spiking Approach Compared to Deep Feedforward Networks on Stepwise Pixel Erasement

在现实世界中，对象经常被部分遮挡。 这要求针对这些扰动的对象识别的鲁棒性。 卷积网络在分类任务中表现出良好的性能。 学到的卷积滤波器似乎类似于在初级视觉皮层中发现的简单细胞的感受野。 或者，尖峰神经网络在生物学上更合理。 我们开发了一个两层的尖峰网络，在自然场景下进行训练，并具有生物学上合理的学习规则。 使用MNIST上逐步像素擦除的分类任务，将其与两个深层卷积神经网络进行比较。 与这些网络相比，尖峰方法具有良好的准确性和鲁棒性。

 

## 2019.12.2~6

### ATIS + SpiNNaker: a Fully Event-based Visual Tracking Demonstration

基于时间的异步图像传感器（ATIS）和尖峰神经网络体系结构（SpiNNaker）都是神经形态技术，“非常规地”使用二进制峰值来表示信息。 ATIS产生尖峰来表示落在传感器上的光的变化，而SpiNNaker是一个大型并行计算平台，可以在内核之间异步发送尖峰进行处理。 在本演示中，我们展示了这两个硬件一起用于执行视觉跟踪任务。 我们旨在展示将ATIS和SpiNNaker集成到一个机器人中间件中的硬件和软件体系结构，该中间件使处理程序与平台无关（CPU或SpiNNaker）。 我们还旨在描述该算法，以及为什么它适用于“非常规”传感器和处理平台，包括优点和面临的挑战。

 

### OPTIMIZING THE ENERGY CONSUMPTION OF SPIKING NEURAL NETWORKS FOR NEUROMORPHIC APPLICATIONS

在过去的几年中，尖峰神经网络已被证明可以与常规卷积神经网络媲美。 几项工作提出了在不显着牺牲性能的情况下将预训练的CNN转换为Spiking CNN的方法。 我们首先证明了CNN的量化感知训练可以提高SNN的准确性。 将CNN转换为尖峰CNN的好处之一是利用SNN的稀疏计算，从而以较低的能耗执行等效的计算。 在这里，我们提出了一种有效的优化策略，以较低的能耗训练尖峰网络，同时保持相似的精度水平。 我们在MNIST-DVS和CIFAR-10数据集上演示了结果



## 2019.11.28

### Technical report: supervised training of convolutional spiking neural networks with PyTorch

近来，已经显示出可以使用时间的反向传播以有监督的方式有效地训练尖峰神经网络（SNN）。确实，最常用的尖峰神经元模型是泄漏的积分并发射神经元，它遵循一个微分方程，可以使用离散的时间步长对其进行近似，从而导致电位的递归关系。点火阈值会导致优化问题，但可以使用替代坡度来解决。在这里，我们以两种方式扩展了先前的方法。首先，我们表明该方法可用于训练卷积层。卷积可以在空间，时间（模拟传导延迟）或两者中进行。其次，我们包括快速水平连接àDenève：当神经元N发射时，我们将权重向量与神经元N之一之间具有相同接受点积的所有神经元的电位相减。如图所示，这对于代表尖峰神经元群体中的动态多维模拟信号很有用。在这里，我们证明，此外，这样的连接还允许实现多维增量发送编码方案。我们在一种语音分类基准上验证了我们的方法：Google语音命令数据集。我们在维持低发射率（约5Hz）的同时，达到了近乎最先进的精度（94％）。我们的代码基于PyTorch，可在http://github.com/romainzimmer/s2net的开源代码中找到。

 

## 2019.11.19

### Unsupervised AER Object Recognition Based on Multiscale Spatio-Temporal Features and Spiking Neurons

本文提出了一种无监督的地址事件表示（AER）对象识别方法。所提出的方法包括输入AER事件的新型多尺度时空特征（MuST）表示和使用依赖于时序定时的可塑性（STDP）进行MuST识别的尖峰神经网络（SNN）。 MuST提取AER事件流的时空信息中包含的特征，同时形成信息量大且紧凑的特征峰值表示。我们不仅展示了MuST如何利用峰值来更有效地传达信息，还展示了它如何使使用SNN的识别受益。识别过程以无监督的方式执行，不需要指定SNN每个神经元的期望状态，因此可以灵活地应用于现实世界中的识别任务。实验在五个AER数据集上进行，其中包括一个名为GESTURE-DVS的新数据集。大量的实验结果表明了该方法的有效性和优势。索引词-地址事件表示（AER），时空特征，尖峰神经网络，无监督学习。

 

### Event-based Object Detection and Tracking for Space Situational Awareness

在这项工作中，我们介绍了使用非常规且很有前途的一类成像设备（称为基于神经形态事件的传感器）进行光学空间成像。这些在人体视网膜上建模的设备不与帧一起工作，而是响应每个像素的对数照明的变化而生成异步事件流。因此，这些设备速度极快，没有固定的曝光时间，可以在设备移动时进行成像，并且在白天和晚上都可以很好地进行低功率空间成像，而无需修改传感器。我们在多个远程站点进行了记录，我们展示了第一个基于事件的空间成像数据集，其中包括来自多个提供商的多个基于事件的传感器的记录，由于此类传感器的匮乏以及操作它们所需的专业知识，大大降低了其他研究人员的进入门槛。所提供的236个独立记录的数据集包含572个标记的居住空间对象，几乎构成了当前所有基于事件的空间成像数据。基于事件的成像范例提出了独特的机遇和挑战，促使开发专门的基于事件的算法，这些算法可以以基于事件的方式执行诸如检测和跟踪之类的任务。在这里，我们研究了用于检测和跟踪的一系列此类基于事件的算法。提出的方法是专门为空间态势感知应用设计的，并评估了准确性，速度和适用于在远程或基于空间的成像平台上的神经形态硬件中实施的术语。尽管在这项工作中我们专注于对空间物体的检测和跟踪，但我们认为这项工作和所提供的数据证明了基于事件的传感器在光学空间成像中的实际应用在广泛的应用中，我们期待着探索未来以及更广泛的天文学界的相关应用。

 

## 2019.11.14

### Action Recognition Using Supervised Spiking Neural Networks

生物神经元使用峰值以能量和计算有效的方式处理和学习时间动态输入。 但是，由于尖峰神经元激活功能的不可微性，将基于梯度的最新监督算法应用于尖峰神经网络（SNN）是一项挑战。 采用替代梯度是克服这一挑战的主要解决方案之一。 尽管SNN在时域中自然起作用，但是最近的研究集中在开发SNN以解决静态图像分类任务上。 在本文中，我们采用替代梯度下降学习算法来识别由动态视觉传感器（DVS）相机记录的十二种人类手势。 提出的SNN可以在测试数据上达到97.2％的识别精度。 关键字：尖刺神经网络，动态视觉传感器，手势识别，替代梯度，监督学习。

 

### Long short-term memory and learning-to-learn in networks of spiking neurons

尖峰神经元（RSNN）的递归网络是大脑惊人的计算和学习能力的基础。但是，至少与人工神经网络（ANN）相比，RSNN模型的计算和学习能力仍然很差。我们解决了两个可能的原因。其中之一是，大脑中的RSNN并不是随机连接或根据简单规则设计的，它们并没有像烟叶网络那样开始学习。相反，大脑的RSNN通过进化，发展和先前的经验针对其任务进行了优化。这些优化过程的细节在很大程度上是未知的。但是，它们的功能贡献可以通过强大的优化方法（例如，时间反向传播（BPTT））进行估算。大脑中RSNN与模型之间的第二个主要不匹配之处在于后者仅显示了大脑中神经元和突触动力学的一小部分。我们将神经元包含在我们的RSNN模型中，该神经元再现了在行为相关的几秒钟内发生的生物神经元的一种重要动力学过程：神经元适应。由于它们的长期记忆，我们将这些网络称为LSNN。如果通过深度学习（BPTT与优化网络体系结构的重新布线算法相结合）进行训练和配置，则包含自适应神经元将大大提高RSNN的计算和学习能力。实际上，这些RSNN的计算性能首次接近LSTM网络。另外，具有适应性神经元的RSNN可以通过“学习到学习”（L2L）方案从先前的学习中获取抽象知识，并转移该知识以便从很少的示例中学习新的但相关的任务。我们将其用于监督学习和强化学习。



## 2019.11.1

### Towards Scalable, Efficient and Accurate Deep Spiking Neural Networks with Backward Residual Connections, Stochastic Softmax and Hybridization

已经有一些建议集中在有监督的（转换，基于尖峰的梯度下降）和无监督的（与尖峰时间相关的可塑性）训练方法上，以提高SNN在大规模任务上的准确性。但是，这些方法中的每一种都受到可伸缩性，等待时间和准确性的限制。在本文中，我们提出了新颖的算法技术，可通过向后残留连接，随机softmax和混合人工加长神经元激活来修改SNN配置，以提高训练方法的学习能力以产生竞争准确性，同时产生较大的效率收益超过他们的人造对手

 

### DashNet: A Hybrid Artificial and Spiking Neural Network for High-speed Object Tracking



事实证明，它们可以在实际复杂的任务上实现令人印象深刻的效果。如何结合这两个模型系列的优势是一个非常有趣的开放问题。两个显著的挑战需要解决：（1）缺乏基准数据集包括两个ANN导向（帧）和SNN导向（尖峰）信号的资源; （2）难以共同处理来自ANN的同步激活和来自SNN的事件驱动峰值。在这项工作中，我们提出了一种混合模式，命名为DashNet，证明在一个模型结合人工神经网络和SNNS的优势。建立了模拟器和基准数据集“ NFS-DAVIS”，并设计了时间互补滤波器（TCF）和注意力模块来分别应对上述两个挑战

