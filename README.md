This utility is needed to process "txt" files into "json" files.

Example: 
From txt.
{{text one}}
{{text @@@two@@@}}}
{{text three}}

into json
{
    "block_00": { "text one",
    "block_01": "text <b>two</b>",
    "block_02": "text three"
}
