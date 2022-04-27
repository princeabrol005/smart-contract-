pragma solidity ^0.5.0;

contract Storage {
string public data = "this is my data";

function change(string memory _data) public returns(string memory){
    data= _data;
    return data;
}

}
