# Market of Walnut Exportation in Chile

The walnut export market is a highly profitable business for the Chilean market. A significant percentage of walnuts produced in Chile is exported to international markets, generating a revenue of USD 394.46 million between January and September 2017 (Muñoz, 2017). In the 2021 season, ChileNut, the **largest trade** association of Chilean walnut producers and exporters, recorded exports of approximately **100,000 tons**, representing an increase of over 20% compared to the 2020 season (ChileNut, 2022). The market is continuously growing, and the commercial walnut plantations in Chile are expanding. It was projected that there would be more than 40,000 hectares of commercial walnut plantations in 2017 (Muñoz, 2017).

### Figure 1


![](https://i.imgur.com/UA5rl5s.jpeg)*Figure 1: Metric tons of exported walnuts with shell.
 Source: Shipment Report December 2021 - (ChileNut, 2022)*

We can observe that Chilean walnut exports continue to grow, even despite the economic setbacks caused by the Covid-19 pandemic.

However, there are challenges in the intermediate process between raw material sales and purchases by exporters. Small and medium-sized producers often **lack knowledge** of the average market prices, and quick sales are hindered because transactions are conducted on a personal basis. Each producer and exporter must establish contact to facilitate the transaction, which is **time-consuming** and results in **non-competitive** prices for both parties. As Matias Rodriguez, General Manager and founder of Nueces del Sur, comments, exporters must make efforts to acquire more customers and compete blindly with limited knowledge of other exporters' offers *(M. Rodriguez, personal communication, September 27, 2022).*

On the other hand, there is not much spot exportation due to the same problem. Consequently, many sales and export processes result in **delayed payments** to the producers, who must cover their expenses and invoices promptly. This situation forces them to seek credit or lines of credit, causing issues in the supply chain and negatively impacting both parties, particularly the producers.


## Scope

The product to be developed has been defined under the name **"AgroTrade"**. Its main function will be to provide a marketplace solution to connect Chilean walnut producers and exporters. The solution will allow the purchase of lots from producers by exporters through a listing of these publications.

On the other hand, transactions will be recorded in real-time, allowing both parties to view a price history of the raw material and provide an updated and real market price for everyone.

The system aims to solve the current problem in the connection mechanism between the mentioned entities. Currently, connections are made **manually** and through **one-on-one conversations**, resulting in missed potential transactions and often leading to non-competitive prices, which can be unfair to different producers. Additionally, it aims to encourage spot exports by streamlining the sales of certain lots to facilitate a more expedited flow of exports and payments to producers.

In summary, the solution proposes a **marketplace-type software** that enables the purchase and sale of raw material lots (walnuts) to Chilean exporters. It streamlines the connection between producers and exporters, promotes spot exports, and improves the flow of exports.

## Level 1 - Process Vision
![Borrador BPMN drawio](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/ebc4adc2-8ad6-4077-8ce3-a45f71de50e4)

### User registration
![User registration](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/cc2b4338-9eba-429e-84c3-69bb5ea470e1)

- **Input**: Customer input.
- **Output**: Successful registration.
- **Description**: This process implies customer input to make a user registration which is later verified by an administrator to make the account available for usage.  
- **Document**: Updated list, Producer/Exporter data.
- **External systems**: N/A.
### User verification
![Account verification](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/966f769e-307c-4c63-b4c0-3c88bf35ca0c)

- **Input**: Successful registration.
- **Output**: N/A.
- **Description**:  This process involves the verification process of a user account by an administrator.
- **Document**: Verification result.
- **External systems**: E-mail.
### Lot publication
![Create publication](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/744bdfc1-45ce-448e-bc2e-94015ea2bef6)

- **Input**: N/A.
- **Output**: Succesful publication.
- **Description**:  This process involves a user creating a new lot publication which will be analyzed in the next process.
- **Document**: Lot detail, Publication result
- **External systems**: E-mail.

### Publication quality analysis
![Quality analysis](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/9fd9c8d1-7fab-4c52-9ea7-9bb687d29fe9)

- **Input**:Successful publication
- **Output**:Analysis approved || Analysis rejected
- **Description**: This process involves the analysis of the previously publicated lot, where the analysist will check the lot that has been publicated and approve or reject the publication.
- **Documents**:Publication status, Quality analysis result
- **External System**:E-mail, Phone
### Reservation
![Reservation](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/cdebfef2-0aef-4282-9ba0-9f96fb61a52b)

- **Input**:Analysis approved
- **Output**:Successful Reservation
- **Description**: This process involves a new reservation for a lot publication which will be then verified by an administrator.
- **Documents**:Transaction information,Exporter data
- **External System**:E-mail
### Transaction
![Transaction](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/2915055e-dbc0-4872-9ef6-2a9352876a56)

- **Input**:Successful Reservation
- **Output**:Completed Transaction
- **Description**: This process involves the administration arranging a meeting with the exporter & producer to settle the payments and shipments of the product.
- **Documents**:Purchase detail, Updated publication list, Producer/Exporter data.
- **External System**: N/A.

### Transaction verification
![Transaction verification](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/10fe9cef-d5e5-4058-b6c7-f108445e43b8)

- **Input**: Completed transaction.
- **Output**: Finalized and verified transaction.
- **Description**: This process involves the check of the payment / shipment status where the administrator & system will notify the producer and exporter if there's any problem with the expected flow. 
- **Document**: Shipment information, updated publication / Transaction list, Purchase detail.
- **External systems**: E-mail, phone.
### Claims & Assesments
![Assesments](https://github.com/tomasrodcas/agro-trade-si/assets/81879787/556fcfcd-3472-41a0-810b-106092162d9f)

- **Input**: Finalized and verified transaction, Problem occurs
- **Output**: Process qualification.
- **Description**:  This process involves the user rating the transaction and the system itself, whether it be for claiming a problem or giving positive assesment.
- **Document**: Claim information, Tracking information, Rating information.
- **External systems**: E-mail.

## Conclussion

The implementation of the "AgroTrade" marketplace software to address the challenges in the walnut export market in Chile would bring several significant benefits to the industry. By connecting producers and exporters through a streamlined platform, the solution would enhance efficiency, transparency, and competitiveness within the market.

Firstly, the software would provide small and medium-sized producers with access to real-time market prices. This knowledge would empower them to make informed decisions and negotiate fair deals, ensuring they receive competitive prices for their walnut lots. By eliminating the current reliance on personal connections, the platform would save time and enable producers to reach a broader range of potential buyers, expanding their market reach.

The introduction of the marketplace software would also foster market transparency. Participants would have access to a price history feature, allowing them to monitor and track market trends. This transparency would encourage fair competition among exporters and ensure that producers receive market-driven prices for their walnut lots. Improved transparency would create a level playing field and enhance trust among market participants.

Additionally, the software would promote collaboration and knowledge-sharing among producers and exporters. By providing a centralized platform, the solution would enable communication and facilitate the exchange of information and insights. This collaborative environment would encourage innovation, best practices, and the overall growth of the industry.

In summary, implementing the "AgroTrade" marketplace software in the walnut export market in Chile would bring numerous benefits. It would empower producers with market knowledge, streamline the sales process, facilitate prompt payments, enhance market transparency, and foster collaboration. These advantages would contribute to a more efficient, competitive, and thriving export market, positioning Chile as a leading player in the global walnut industry.
