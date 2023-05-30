# url-shortener-api
a simple but powerful url shortener api


Endpoint : https://iysabox.com/api/short-url?link={link}


Request :

fetch("https://iysabox.com/api/short-url?link=https://google.com")
    .then(res => res.json())
    .then(data => {
	    console.log(data)
    })


Response :

{
    "status" : "success",
    original_link : https://google.com
    shorted_link : "https://iysabox.com/r/OW2vaD1bO1"
}

