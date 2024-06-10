# Sample Anti-Fraud system with NLP(ML) for banking

// description

## Features
- [ ] We need custom ML(NLP) model
- [ ] Program teaches model in runtime
- [ ] Create service which is manages NLP model. Methods: `teach, replace, add info`. Don't implement delete model method
- [ ] Add docs

## Test cases
1. User already has transactions, and user creates transaction with high amount -> Should block
2. User already has transactions and all transactions are created in Uzbekistan, and user creates transaction in another country or region -> Should block
3. User creates transactions with small amount but again and again - Should block
4. User swaps currency from `UZB` to `UZD` but more times -> Should block
5. User creates transaction with another IP address -> Should block(Suspicious)

## Technologies
- [Apache Flink](https://flink.apache.org/)
- [Apache OpenNLP](https://opennlp.apache.org/)

## Team space
### Developers
- Sardor Shorahimov