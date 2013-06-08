Message-Passing-Utils
=====================

some plugins for suretec/Message-Passing

# Message-Passing-Filter-Regexp

Just works. like `Grok` of `logstash`.

# Message-Passing-Output-ElasticSearch

Modify suretec/Message-Passing-Output-ElasticSearch for `@fields` structs.

Attention: using `delete` function in `consume` caller, so if you want use 
Message::Passing::Filter::T to multi-output, please list `output es` at the
last one.

# Message-Passing-Output-PocketIO

Run Twiggy Server listenned 8080 to output message by websocket
