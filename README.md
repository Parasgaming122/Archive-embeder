# Archive-embeder
Embed archive.org mp4 series
Example 
const baseUrl = 'https://archive.org/download/garo-2005/%282005%29%20GARO/%5BGomenRider%5D%20GARO%20%282005%29%20';
change the baseurl to the thing you want 
const episodeNumber = `E${i.toString().padStart(2, '0')}`; format for E23
or 
const episodeNumber = `Ep ${i}.mp4`; format for Ep 3.mp4

change 25 with max ep number 
    for (let i = 1; i <= 25; i++) {


OR give the code to ai and use this prompt 
now this is the base url {Baseurl} and this is the ep format {Epformat} and instead of 25 max is {max epno}     for (let i = 1; i <= 25; i++) {

