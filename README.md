# projectParisPublic
A public view of a private project. Weakpoint detection under weather events for a european power system
<img width="2492" height="1323" alt="Figure_1" src="https://github.com/user-attachments/assets/09b9bdb8-7da7-4953-994a-4c7a3b420572" />
This first image is from the Optimal Power Flows that were made during the first 10 months of 2024 (synthetic data) for the entirety of the German power grid (with neighboring countries as single nodes). X-axis is the removed line, and Y-axis is the difference in operational expenditure compared to basecase.

In overfitting experiments the EV_GNNmassively outperformed the GCN. The latter could get hold of no signal - prob due to single edge-parameter of GCN. A FFN had a similar result as the EVGNN, but had 10² more parameters.
EVGNN, GCN and FFN each trained on 10 MTU and 100, 500, 500 epochs resp.

<img width="800" height="500" alt="10mtu100epoch_ev" src="https://github.com/user-attachments/assets/c1f5a392-3702-47ee-8155-45e41186e87a" />

<img width="800" height="500" alt="10mtu500epoch_gnn" src="https://github.com/user-attachments/assets/3571ee6f-1aaf-4609-ad66-29bbcb638e8a" />

<img width="799" height="499" alt="10mtu500epoch_mlp" src="https://github.com/user-attachments/assets/99564558-1252-473e-95bf-a5f8909a9f03" />
