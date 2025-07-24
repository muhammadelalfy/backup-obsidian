there are two types of apis 

programming apis 
like console.log . document.write

web api 

third party apis like google apis 

http / hyper text transfer protocol

use it for making web apis 

every http request and its response have header and body in both 

http methods get , post . patch , delete 

methods sent in req header 

accept application json to tell the server that i want the response as json 

fetch to make http request 

const url = 'https://countriesnow.space/api/v0.1/countries';

fetch(url, {

method: 'GET',

headers: {

'accept': 'application/json',

}

})

.then(response => response.json())

.then(data => console.log(data))

.catch(error => console.error('Error fetching data:', error));

