This is the Data Preparation step for END2.0 Capstone.


The final dataset must look like this:

Example 1:
x: Question: Why is PyTorch better than Keras?
z: Answer Document: In my opinion, this is a very personal question. Every developer/person would have his/her own comfort level while deciding on which platform suits them. I will share my opinion. I think PyTorch is better because it is pythonic, (literally like python and you do not need to learn anything new), has higher performance, strong community support, most new papers are written using PyTorch, and has dynamic computation graphs. But again, I might be biased towards it, and maybe you may like something that is better in Keras than Pytorch and might decide to go ahead with it.
y: Exact Answer: PyTorch is better because it is pythonic, has higher performance, has strong community support, most new papers are written using PyTorch, and has dynamic computation graphs.

Example 2:
x: Question: torch.tensor.new_tensor:
z: Answer Document: https://pytorch.org/docs/stable/generated/torch.Tensor.new_tensor.html#torch.Tensor.new_tensor (Links to an external site.)
y: Exact Answer: Tensor.new_tensor(data, dtype=None, device=None, requires_grad=False) → Tensor
Returns a new Tensor with data as the tensor data. By default, the returned Tensor has the same torch.dtype and torch.device as this tensor.

TEAM MEMBERS: Sachin D, Debasish Sarangi, Pavithra Solai, Anirban Mukherjee, Smruthi SR, Krishna N Revi, Asha Anbarasi, Pankaj Goyal.
Our team worked on Stackoverflow data extraction and annotation.

The Stackoverflow Question and answer annotation on which i have worked is -

https://github.com/debasishsarangi88/TSAI_END2.0/blob/main/Capstone/Dataprep/qna_stackoverflow_Debasish.xlsx

Combined Stackoverflow team excel file -

https://github.com/debasishsarangi88/TSAI_END2.0/blob/main/Capstone/Dataprep/Combined_annotated_QandA_stackoverflow_v3.xlsx

The complete Json file of stackoverflow team is -

https://github.com/debasishsarangi88/TSAI_END2.0/blob/main/Capstone/Dataprep/Stackoverflow_QandA_v3.json
