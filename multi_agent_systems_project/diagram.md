```mermaid
flowchart TD
    %% ======= Nodes =========
    CR(Customer_Request)
    OR(Orchestrator)
    IM(Inventory_Manager)
    QG(Quote_Generator)
    OFM(Order_Fulfillment_Manager)

    %% ======= Edges =========
    CR --> OR
    OR <--> IM
    OR <--> QG
    OR <--> OFM


```
