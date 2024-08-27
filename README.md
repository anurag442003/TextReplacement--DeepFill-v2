## instructions: 
1. enable google vision api
### set credentials
$env:GOOGLE_APPLICATION_CREDENTIALS=path_to_credentials.json

## Execution:
python final_replace.py --image [path_to_input_image] --search_text [text_to_be_replaced] --replace_text [new_text] --checkpoint pretrained/states_pt_places2.pth --output [path_to_output_image]
