# HTML��XML��XHTML ��ʲô����
- HTML�����ı�������ԣ����﷨��Ϊ��ɢ�ġ����ϸ��Web���ԣ�
- XML������չ������ԣ���Ҫ���ڴ洢���ݺͽṹ��
- XHTML������չ���ı�������ԣ�����XML��������HTML���ƣ����﷨���ϸ�

# ������� HTML ���廯
HTMLһֱ�ڳ����廯�ķ���չ��
- ���廯���ڼ������Ϳ����߸����׶������룬������SEO�����Ը��õ�����������ץȡ������ĵ���
- ���廯���������Ӿ��ϰ�����Ⱥ���Ի�ȡҳ����Ϣ��
- W3C�Ƴ���HTML5��һ���ƽ������廯��չ������nav��footer�����廯��ǩ���ֲ��˲���id="footer"����class="footer"��ʽ�Ĳ��㣬�Ը��õ��ƶ�Web�ķ�չ��
- ��ʡά���ɱ�����߿���Ч��

# ���������������ʽ�����ԭ��
- �����������������ʽ
- ���Խ��ͺ���ά���ɱ�����߿���Ч��
- ���������ʽ����ĸ�����
- ��HTML�ṹû����ʽ���������Ȼ�������廯����ʾ���ݣ�������ʽӰ��

# ����Щ������meta��ǩ
META��ǩ��������һ��HTML��ҳ�ĵ������ԣ��������ߡ����ں�ʱ�䡢��ҳ�������ؼ��ʡ�ҳ��ˢ�µȡ�
META��ǩ�ɷ�Ϊ���󲿷֣�HTTP-EQUIV��NAME������
HTTP-EQUIV��
```
<meta http-equiv="Content-Type" content="text/html;charset=utf-8">�ַ�������Ϊutf-8
<meta http-equiv="Content-Language" content="zh-CN">��������Ϊ����
<meta http-equiv="Refresh" content="n;url=http://yourlink">��ʱ����ҳ��ָ����ʱ��n�ڣ���ת�����ҳ��
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">���������汾ѡ����Ⱦ������
<meta http-equiv="Expires" content="Mon,12 May 2001 00:20:00 GMT">cookie�趨�������ҳ���ڣ����̵�cookie����ɾ��
<meta http-equiv="Pragma" content="no-cache">�����趨��ֹ������ӱ��ػ��Ļ����е���ҳ������
<meta http-equiv="Page-Enter" content="revealTrans��duration=10,transition= 50��">�趨����ҳ��ʱ������Ч��
<meta http-equiv="Page-Exit" content="revealTrans��duration=20��transition=6��">�趨������뿪ҳ��ʱ������Ч��
<meta http-equiv="windows-Target" content="_top">ǿ��ҳ���ڵ�ǰ�������Զ���ҳ����ʾ����ֹ��ҳ������frameҳ����
```
NAME��һ�����title��ǩ���棩��
```
<meta name="keywords" content="�Ʊ� ղķ˹" />�ؼ���
<meta name="description" content="NBA������ְҵ��������" />��վ������������������������ʾ����վ��������Ȼ���ԣ��ǹؼ��ʣ�������SEO
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" >��ҳ�Ӵ�������ĳ����ڸ����豸����
<meta name="Author" content="" />����
```

# �ĵ�����������?�ϸ�ģʽ�ͻ���ģʽָʲô?<!doctype html> ������?
- <!DOCTYPE>����λ��λ��HTML�ĵ��еĵ�һ�У����� <html> ��ǩ֮ǰ����֪������Ľ�������ʲô�ĵ���׼��������ĵ���DOCTYPE�����ڻ��ʽ����ȷ�ᵼ���ĵ��Լ���ģʽ���֡�
- �ϸ�ģʽ��Ҳ�б�׼ģʽ����׼ģʽ���Ű��JS����ģʽ�����Ը������֧�ֵ���߱�׼���С�
����ģʽ��Ҳ�м���ģʽ���ڼ���ģʽ�У�ҳ���Կ��ɵ������ݵķ�ʽ��ʾ��ģ����ʽ���������Ϊ�Է�ֹվ���޷�������
- <!doctype html>����������ǰ�ĵ�Ϊhtml5������
HTML5������SGML����˲���Ҫ��DTD�������ã�������ҪDOCTYPE���淶���������Ϊ�����������������Ӧ�õķ�ʽ�����У���
HTML4.01����SGML��������Ҫ��DTD�������ã������������֪�����ĵ���ʹ�õ��ĵ����͡�

# ����������ԭ����ʲô����ν��
- �����ԭ��ͨ�׵㽲�����ĵ�����ı����ʽ���ĵ���������charset��һ�µ��µġ�
- ������ļ������ʽ���ĵ���charsetҪһ�¡�
[����������](https://zhuanlan.zhihu.com/p/24465635?refer=study-fe)

# ���������������Щ��ʲô�ں�
- �����������Chrome��IE��Firefox��Opera��Safari��
- Trident�ںˣ�IE,MaxThon,TT,The World,360,�ѹ�������ȡ�[�ֳ�MSHTML]
Gecko�ںˣ�Netscape6�����ϰ汾��FF,MozillaSuite/SeaMonkey��
Presto�ںˣ�Opera7�����ϡ�      [Opera�ں�ԭΪ��Presto����Ϊ��Blink;]
Webkit�ںˣ�Safari,Chrome�ȡ�   [ Chrome�ģ�Blink��WebKit�ķ�֧��]
[������ں˵Ľ����ͶԱ�](http://www.cnblogs.com/fullhouse/archive/2011/12/19/2293455.html)

# �г������ı�ǩ�����򵥽�����Щ��ǩ����ʲô����
```
<!DOCTYPE>�����ĵ�����
<html>���������� HTML �ĵ�
<head>��������ĵ�����Ϣ
<title>��ҳ�ı���
<meta>������� HTML �ĵ���Ԫ��Ϣ
<link>һЩ�����ļ�����
<script>����ͻ��˽ű�
<style>�����ĵ�����ʽ��Ϣ
<!--...-->ע��
<body>HTML �ĵ�������
<h1>-<h6 >HTML ����
<em>ǿ���ı�
<form>���幩�û������ HTML ��
<a>ê
<span>��������ĵ��е�����Ԫ�أ��ʵ���ǿ����
<img>ͼƬ��ǩ
<input >����ؼ�
<button>��ť
<select >ѡ���б������б�
<strong >ǿ��������
<div>��Ԫ��
<ul>�����б�
<ol>�����б�
<li>�б����Ŀ
<dl>�����б�
<dt>�����б��е���Ŀ
<dd>�����б��е���Ŀ������
<table>������
<caption>���������
<th>�������еı�ͷ��Ԫ��
<tr>�������е���
<td>�������еĵ�Ԫ
<p>���ֶ���
<br>����
```