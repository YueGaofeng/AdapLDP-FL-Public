# AdapLDP-FL
A novel adaptive LDP to optimize the performance of the FL system.
Federated Learning (FL) is a technique that allows multiple participants to co-train machine learning models, while also
enhancing privacy by avoiding the exposure of local data. However, it is important to note that despite its effectiveness, there is still a
potential risk of leaking users’ private information through weight analysis during FL updates. Local Differential Privacy (LDP) is a
technique used to prevent individual information leakage by adding noise to the user’s model parameters. However, FL based on LDP
lacks dynamic optimization and adaptation considering privacy and data utility, especially regarding noise constraints. This paper
investigates FL under the scenario of noise optimization with LDP. Specifically, given a certain privacy budget, we design the adaptive
LDP method via a noise scaler, which adaptively optimizes the noise size of every client. Secondly, we dynamically tailor the model
direction after adding noise by the designed a direction matrix, to overcome the model drift problem caused by adding noises to the
client model. Finally, our method achieves higher accuracy than some existing works with the same privacy level and the convergence
speed is significantly improved.
