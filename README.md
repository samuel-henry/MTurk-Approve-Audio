MTurk-Approve-Audio
======================

Files for getting audio recordings of words reviewied / re-recorded if necessary

Based on aws-mturk-clt-1.3.1/samples/external_hit

To post HITs:
sh loadHits.sh -input ./approve_audio/external_hit.input -question ./approve_audio/external_hit.question -properties ./approve_audio/external_hit.properties -label external_hit

To get results:
sh getResults.sh -successfile external_hit.success -outputfile external_hit.results

To delete HITs:
sh deleteHits.sh -successfile external_hit.success -expire
