Protobuf specifications for [Flightmate-Stream](https://github.com/Flightmate/Flightmate-Stream)

To compile yourself (should not be neccessary for OTAs): 
- protoc --proto_path=. another_click_packet.proto --go_out=.
- protoc --proto_path=. another_search_packet.proto --go_out=.
- Remember that you have to edit to package "message" in the generated .go file