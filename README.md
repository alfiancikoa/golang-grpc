# golang-grpc
Basic materi about grpc to transfer data between service and client 

doc grpc <a href="https://grpc.io/" target="_blank" rel="noopener noreferrer"><b>here</b></a>

<p align="justify"><b>gRPC</b> atau biasa dikenal dengan <b>Google Remote Procedure Call</b> merupakan framework <b>Remote Procedure Call</b> yang bersifat open source yang dikembangkan oleh Google pada tahun 2015 sebagai generasi selanjutnya dari infrastruktur RPC. gRPC menggunakan HTTP/2 untuk transportasi, ProtoBuff atau Protocol Buffers sebagai bahasa deskripsi antarmuka, dan menyediakan fitur seperti autentikasi, streaming dua arah, flow control, blocking and unblocking bindings, dan pembatalan serta timeout.
<br>
(Sumber: https://en.wikipedia.org/wiki/GRPC)
</p> 

### Command to use

- install golang-rpc di internal, more info: <a href="https://grpc.io/docs/protoc-installation/">here</a>
```
#Linux, using apt or apt-get, for example:
$ apt install -y protobuf-compiler
$ protoc --version  # Ensure compiler version is 3+

# MacOS, using Homebrew:
$ brew install protobuf
$ protoc --version  # Ensure compiler version is 3+
```
