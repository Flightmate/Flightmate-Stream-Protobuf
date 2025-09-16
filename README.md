Protobuf specifications for [Flightmate-Stream](https://github.com/Flightmate/Flightmate-Stream)

To compile yourself (should not be neccessary for OTAs): 
- protoc --proto_path=. --go_out=. search_packet.proto
- protoc --proto_path=. --go_out=. click_packet.proto