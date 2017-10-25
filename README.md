# redirect.py
UPDATED!  we add an awesome payloads list by https://github.com/cujanovic/Open-Redirect-Payloads

Open redirect Scanner by Ak1t4 - https://hackerone.com/ak1t4
(contributor(s): @sxcurity)


Use ./redirect.py [subdomains.file] [redirect-payload]

Example ./redirect.py uber.list '//yahoo.com/%2F..'


UPDATE:  (Now is not necesary indicate the payload we replace we an entire payloads list)

this is pretty awesome, now you can run 1 only command who search all subdomains in 1 file and inject unlimited Payloads from payloads.list

Use example:

skynet-localhost:Sublist3r ak1t4_hax0r$  while read -r line;do python redirect.py.1 uber.list $line;done < payloads.list 


Here is a new video PoC with the unlimited payloads -> https://youtu.be/hCWxb88do2I

This is the old video PoC  -> https://www.youtube.com/watch?v=esMBWSO4RUU

Enjoy!

@ak1t4



