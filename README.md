Protobuf specifications for [Flightmate-Stream](https://github.com/Flightmate/Flightmate-Stream)

The field ShowresultId is only used for our testing of the stream. 

To compile yourself (should not be neccessary for OTAs): 
- protoc --proto_path=. another_click_packet.proto --go_out=.
- protoc --proto_path=. another_search_packet.proto --go_out=.
- Remember that you have to change the package name to "click_packet"/"search_packet" in the generated .go file