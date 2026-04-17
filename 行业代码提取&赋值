encode indcode, gen(ind_id)
order ind_id, after(indcode) 

* substr(var,n1,n2), 对于字符文本或字符型变量var, 提取规则：从第n1位开始, 提取文本长度为n2。 
gen indcode1 = substr(indcode, 1, 1) //提取首位行业代码
order indcode1, after(region4id) 

encode indcode1, gen(ind1_id)
order ind1_id, after(indcode1) 
