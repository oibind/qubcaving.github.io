### Building with Docker on Apple Silicon

``docker build --platform linux/amd64 -t qubcc . && docker run --platform linux/amd64 -p 4000:4000 -v `pwd`:/app qubcc``

### Todo

-  Make pretty ✅
- Add multipage support
- Add RSS for [Substack](https://substack.com/@qubcaving)
