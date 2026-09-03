# LinkReview

- Here we have collect info about all the works that may be useful for writing our paper
- We divide these works by topic in order to structure them

> [!NOTE]
> This review table will be updated, so it is not a final version

| Topic | Title | Year | Authors | Paper | Code | Summary |
| :--- | :--- | ---: | :--- | :--- | :--- | :--- |
| **Neural ODE / Normalizing Flows** | Neural ordinary differential equations | 2018 | Ricky T. Q. Chen et al. | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2018/hash/69386f6bb1dfed68692a24c8686939b9-Abstract.html) | TODO | Основная статья по непрерывным нормализующим потокам |
| | Free-form continuous dynamics for scalable reversible generative models | 2018 | W. Grathwohl et al. | [arXiv](https://arxiv.org/abs/1810.01367) | TODO | Ранняя работа по обучению непрерывных нормализующих потоков |
| | Normalizing flows: An introduction and review of current methods | 2020 | I. Kobyzev et al. | [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9089305) | TODO | Обзор по нормализующим потокам |
| | Normalizing flows for probabilistic modeling and inference | 2021 | G. Papamakarios et al. | [JMLR](https://www.jmlr.org/papers/v22/19-1028.html) | TODO | Обзор по нормализующим потокам |
| **Diffusion Models** | Deep unsupervised learning using nonequilibrium thermodynamics | 2015 | J. Sohl-Dickstein et al. | [PMLR](https://proceedings.mlr.press/v37/sohl-dickstein15.html) | TODO | Первая работа по диффузиям |
| | Generative modeling by estimating gradients of the data distribution | 2019 | Y. Song & S. Ermon | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2019/hash/3001ef257407d5a371a96dcd947c7d93-Abstract.html) | TODO | Одна из двух основополагающих работ по диффузионным моделям (score-based) |
| | Denoising diffusion implicit models | 2020 | J. Song et al. | [arXiv](https://arxiv.org/abs/2010.02502) | TODO | Диффузионные вероятностные модели с шумоподавлением |
| | Score-based generative modeling through stochastic differential equations | 2020 | Y. Song et al. | [arXiv](https://arxiv.org/abs/2011.13456) | TODO | Диффузионные SDE, база для CSDI для импутации |
| **Flow Matching** | Flow matching for generative modeling | 2022 | Y. Lipman et al. | [arXiv](https://arxiv.org/abs/2210.02747) | TODO | Основы метода Flow Matching, первая статья |
| | Building normalizing flows with stochastic interpolants | 2022 | M. S. Albergo & E. Vanden-Eijnden | [arXiv](https://arxiv.org/abs/2209.15571) | TODO | Теоретическая работа, близкая к Flow Matching (строят потоки через стохастические интерполянты) |
| | Matching normalizing flows and probability paths on manifolds | 2022 | H. Ben-Hamu et al. | [arXiv](https://arxiv.org/abs/2207.04711) | TODO | Непрерывные нормализующие потоки на многообразиях через минимизацию расхождения траекторий вероятностей |
| | Improving and generalizing flow-based generative models with minibatch optimal transport | 2024 | A. Tong et al. | [arXiv](https://arxiv.org/abs/2302.00482) | TODO | Развитие Flow Matching с использованием оптимального транспорта для улучшения качества генерации |
| | A downsampled variant of imagenet as an alternative to the cifar datasets | 2017 | P. Chrabaszcz et al. | [arXiv](https://arxiv.org/abs/1707.08819) | [GitHub](https://github.com/PatrykChrabaszcz/Imagenet32_Scripts) | Облегченный бенчмарк для обучения глубоких нейронных сетей |
| **Imputation** | CSDI: Conditional score-based diffusion models for probabilistic time series imputation | 2021 | Y. Tashiro et al. | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2021/hash/cfe8504bda37b575c70ee1a8276f3486-Abstract.html) | TODO | Диффузионная модель импутации временных рядов с фиксацией наблюдаемых значений |
| | CFMI: flow matching for missing data imputation | 2025 | V. Simkus et al. | [arXiv](https://arxiv.org/abs/2506.09258) | TODO | Conditional Flow Matching для импутации пропусков в общем виде |
| | Time-Gated Multi-Scale Flow Matching for Time-Series Imputation | 2026 | H. Wang et al. | [ICLR](https://openreview.net/forum?id=51d317df78eded9eb3c9d3fb1091c279) | TODO | Учат векторное поле через Flow Matching с маскированным контролем скорости только на пропущенных координатах |
| | Impute-MACFM: Imputation based on Mask-Aware Flow Matching | 2025 | D. Liu et al. | [arXiv](https://arxiv.org/abs/2509.23126) | TODO | Mask-aware conditional flow matching для табличных и лонгитудинальных данных с траекториями только на пропущенных элементах |
| | Spatiotemporal Imputation with Graph-Informed Flow Matching | 2026 | Z. Zhang et al. | [arXiv](https://arxiv.org/abs/2606.06682) | TODO | Замена гауссова прайора на граф-информированный через пространственно-временную фильтрацию наблюдаемых сигналов |
| **EEG Imputation** | Missing Data Gap Imputation Methods in Electroencephalogram (EEG) Signals: A Systematic Scoping Review | 2026 | T. Bergmann et al. | [MDPI](https://www.mdpi.com/1424-8220/26/8/2431) | TODO | Обзор методов восстановления пропусков в ЭЭГ |
| | Contextual imputation with missing sequence of EEG signals using generative adversarial networks | 2021 | W. Lee et al. | [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9606711/) | TODO | Использование GAN для восстановления пропусков в ЭЭГ как задачи генерации последовательностей |
| | SRI-EEG: state-based recurrent imputation for EEG artifact correction | 2022 | Y. Liu et al. | [Frontiers](https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2022.803384/full) | TODO | Рекуррентный подход для коррекции артефактов и импутации в ЭЭГ |
| | Spatial imputation drives cross-domain alignment for EEG classification | 2025 | H. Liu et al. | [ACM](https://dl.acm.org/doi/abs/10.1145/3746027.3755582) | TODO | Пространственная импутация для согласования доменов при классификации ЭЭГ |
| | Imputing missing values in EEG with multivariate autoregressive models | 2018 | A. Kanemura et al. | [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/8512790/) | TODO | Восстановление пропусков в многомерных рядах ЭЭГ (классический бейзлайн) |
| **EEG + Flow Matching** | NeuroSonic: Conditional Flow Matching for EEG-to-Speech Reconstruction | 2026 | W. Gao et al. | [arXiv](https://arxiv.org/abs/2606.24087) | TODO | Применение Conditional Flow Matching к ЭЭГ-сигналам — учит векторное поле, переносящее зашумлённый сигнал в чистый под условием ЭЭГ |
| | Let EEG Models Learn EEG | 2026 | Y. Wang et al. | [arXiv](https://arxiv.org/abs/2605.21280) | TODO | Генеративная модель ЭЭГ на основе Conditional Flow Matching, работающая с непрерывными траекториями сигналов |
| **EEG + Graph / Topology** | EpiTwin: Spatiotemporal Graph Transformers for Epileptic sEEG Signal Reconstruction | 2026 | J. Yang et al. | [ICLR](https://openreview.net/forum?id=wmyNZRBBKv) | TODO | Использование пространственных координат электродов, топологии графа и анатомических априорных знаний для реконструкции сигнала |
| | Signal reconstruction from incomplete time-varying EEG via local and global graph learning | 2025 | Y. Cao et al. | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1051200425006694) | TODO | Интеграция локальных и глобальных графовых структур для моделирования пространственных связей в мозговой активности |
| **SURVEY** | A Survey on Missing Data Generation in Networks | 2026 | Q. Shao et al. | [MDPI](https://www.mdpi.com/2227-7390/14/2/341) | TODO | Обзор методов генерации пропущенных данных в сетевых структурах |
| | Diffusion and Flow Matching Models for Tabular Data: A Survey | 2026 | Z. Li et al. | [arXiv](https://arxiv.org/abs/2502.17119) | TODO | Первый обзор, посвящённый диффузионным моделям и Flow Matching для табличных данных |
| | A survey on diffusion models for time series and spatio-temporal data | 2026 | Y. Yang et al. | [ACM](https://dl.acm.org/doi/abs/10.1145/3783986) | TODO | Подробный обзор диффузионных моделей для временных рядов и пространственно-временных данных |
| | TODO | TODO | TODO | [arXiv](https://arxiv.org/abs/2011.13456) | TODO | TODO |
