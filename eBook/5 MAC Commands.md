

# **��5�� MAC����**

����������߶��ԣ���һ��ר�ŵ�MAC���������ڷ��������ն�MAC��֮�佻��������MAC�����Ӧ�ó���(�����Ƿ������˻����ն��豸��Ӧ�ó���)�ǲ��ɼ��ġ�

��������֡�п���Я��MAC���Ҫô��FOpts�ֶ����Ӵ���Ҫô�ڶ���֡�н�FPort���0�����FRMPayload��������FOpts�Ӵ��ķ�ʽ��MAC�����ǲ����ܲ��Ҳ����ȳ���15�ֽڡ�������ö���֡����FRMPayload�ķ�ʽ���Ǿͱ�����ü��ܷ�ʽ�����Ҳ�����FRMPayload����󳤶ȡ�

> ע�⣺���MAC����뱻�������Ǿͱ����Զ���֡��ʽ����FRMPayload�С�

ÿ��MAC�������� 1�ֽ�CID ����һ�ο���Ϊ�յ��ֽ����� ��ɵġ�

<table>
   <tr>
      <td rowspan="2" ><b>CID</b></td>
      <td rowspan="2" ><b>Command</b></td>
      <td colspan="2" ><b>��˭����</b></td>
	  <td rowspan="2" ><b>����</b></td>
   </tr>
   <tr>
      <td>�ն�</td>
      <td>����</td>
   </tr>
   <tr>
      <td>0x02</td>
      <td>LinkCheckReq</td>
      <td>x</td>
      <td></td>
	  <td>�ն���������������ж�������������</td>
   </tr>
   <tr>
      <td>0x02</td>
      <td>LinkCheckAns</td>
      <td></td>
      <td>x</td>
	  <td>LinkCheckReq�Ļظ������������ź�ǿ�ȣ���֪�ն˽�������</td>
   </tr>
   <tr>
      <td>0x03</td>
      <td>LinkADRReq</td>
      <td></td>
      <td>x</td>
	  <td>���ն�����ı��������ʣ����书�ʣ��ش����Լ��ŵ�</td>
   </tr>
   <tr>
      <td>0x03</td>
      <td>LinkADRAns</td>
      <td>x</td>
      <td></td>
	  <td>LinkADRReq�Ļظ���</td>
   </tr>
   <tr>
      <td>0x04</td>
      <td>DutyCycleReq</td>
      <td></td>
      <td>x</td>
	  <td>���ն����÷��͵����ռ�ձȡ�</td>
   </tr>
   <tr>
      <td>0x04</td>
      <td>DutyCycleAns</td>
      <td>x</td>
      <td></td>
	  <td>DutyCycleReq�Ļظ���</td>
   </tr>
   <tr>
      <td>0x05</td>
      <td>RXParamSetupReq</td>
      <td></td>
      <td>x</td>
	  <td>���ն����ý���ʱ϶������</td>
   </tr>
   <tr>
      <td>0x05</td>
      <td>RXParamSetupAns</td>
      <td>x</td>
      <td></td>
	  <td>RXParamSetupReq�Ļظ���</td>
   </tr>
   <tr>
      <td>0x06</td>
      <td>DevStatusReq</td>
      <td></td>
      <td>x</td>
	  <td>���ն˲�ѯ��״̬��</td>
   </tr>
   <tr>
      <td>0x06</td>
      <td>DevStatusAns</td>
      <td>x</td>
      <td></td>
	  <td>�����ն��豸��״̬���������������·���Ԥ�㡣</td>
   </tr>
   <tr>
      <td>0x07</td>
      <td>NewChannelReq</td>
      <td></td>
      <td>x</td>
	  <td>�������޸� 1����Ƶ�ŵ� ���塣</td>
   </tr>
   <tr>
      <td>0x07</td>
      <td>NewChannelAns</td>
      <td>x</td>
      <td></td>
	  <td>NewChannelReq�Ļظ���</td>
   </tr>
   <tr>
      <td>0x08</td>
      <td>RXTimingSetupReq</td>
      <td></td>
      <td>x</td>
	  <td>���ý���ʱ϶��ʱ�䡣</td>
   </tr>
   <tr>
      <td>0x08</td>
      <td>RXTimingSetupAns</td>
      <td>x</td>
      <td></td>
	  <td>RXTimingSetupReq�Ļظ���</td>
   </tr>
   <tr>
      <td>0x80~0xFF</td>
      <td>˽��</td>
      <td>x</td>
      <td>x</td>
	  <td>��˽������������չ��Ԥ����</td>
   </tr>
</table>
��4��MAC�����

> ע�⣺MAC����ĳ�����Ȼû����ȷ����������MACִ�в����Ҫ֪�������δ֪��MAC�����޷������ԣ���ǰ��δ֪��MAC�������ֹMAC����Ĵ�����С����Խ��鰴��LoRaWANЭ����ܵ�MAC����������MAC����������л���LoRaWANЭ���MAC������Ա�������ʹ�Ǹ��߰汾�����

---
## <a name="5.1">5.1 Link Check ���� (LinkCheckReq, LinkCheckAns)</a>

## <a name="5.2">5.2 Link ADR ����(LinkADRReq, LinkADRAns)</a>

ͨ�� LinkADRReq ���NS(���������)���Ե����ն˵����ʡ�

<table>
   <tr>
      <td><b>Size (bytes)</b></td>   
      <td>1</td>   
	  <td>2</td>  
	  <td>1</td>  
   </tr>
   <tr>
      <td><b>LinkADRReq Payload</b></td>
      <td>DataRate_TXPower</td>
	  <td>ChMask</td>
	  <td>Redundancy</td>
   </tr>
</table>

<table>
   <tr>
      <td><b>Bits</b></td>   
      <td>[7:4]</td>   
	  <td>[3:0]</td>  
   </tr>
   <tr>
      <td><b>DataRate_TXPower</b></td>
      <td>DataRate</td>
	  <td>TXPower</td>
   </tr>
</table>

���������������(DataRate)�ͷ��书��(TXPower)�Ǹ�������涨��������[LoRaWANЭ�����İ�_�����ļ� ��������(�����) ](http://blog.csdn.net/iotisan/article/details/55056092)�С������еķ��书���ֶ�ָ�����豸�ɲ���������书�ʡ���������еķ��书�ʸ����ն�ʵ�ʷ��书�ʵ����ֵ���ն�ҲҪӦ��ɹ�����������£����ն˵ķ��书�ʾ�������ߵ����ֵ�� ChMask �ֶ�ָʾ�����еĿ����ŵ��������λbit0��ʾ��ʼ��

<table>
   <tr>
      <td><b>Bit#</b></td>   
      <td><b>Usable channels</b></td>   
   </tr>
   <tr>
      <td>0</td>
      <td>Channel 1</td>
   </tr>
   <tr>
      <td>1</td>
      <td>Channel 2</td>
   </tr>
   <tr>
      <td>..</td>
      <td>..</td>
   </tr>
   <tr>
      <td>15</td>
      <td>Channel 16</td>
   </tr>
</table>
��5���ŵ�״̬��

ChMask �ֶεĶ�Ӧλ�������Ϊ1�����ʾ��Ӧ���ŵ����Խ������д��䣬ֻҪ���ŵ������ն�ʹ�ø��������ʡ������Ӧλ����Ϊ0�����ʾ��Ӧ�ŵ������á�

<table>
   <tr>
      <td><b>Bits</b></td>   
      <td>7</td>   
	  <td>[6:4]</td>  
	  <td>[3:0]</td>  
   </tr>
   <tr>
      <td><b>Redundancy bits</b></td>
      <td>RFU</td>
	  <td>ChMaskCntl</td>
	  <td>NbTrans</td>
   </tr>
</table>

Redundancy �ֶ��е� NbTrans λ��ָ����ÿ��������Ϣ�ķ��͸���������� "unconfirmed" ��Ϣ�����á����ڵ�֡���������Ӧ��Ĭ��ֵΪ1����Ч��Χ��[1:15]������յ� NbTrans == 0���ն���Ҫ��Ĭ��ֵ�����λ����Ա�NS(���������)�������ƽڵ����е� Redundancy �Ӷ����QOS(��������)�����ش�֡ʱ�ڵ�ͨ�����Ƶ��ÿ���ش����õȵ����մ��ڳ�ʱ��ֻҪ��RX1�ڼ��յ�������Ϣ����������Ϣ���ٽ����κ��ش������� Class A �豸��RX2ʱ϶�Ľ���Ҳ��һ������

ChMaskCntl λ���֮ǰ����� ChMask �ֶ��йأ���������ChMask��ָ����16���ŵ��顣Ҳ���Զ������ŵ�����ȫ�ֵĴ򿪻�رա����λ���ʹ���Ǹ�������涨��������[LoRaWANЭ�����İ�_�����ļ� ��������(�����) ](http://blog.csdn.net/iotisan/article/details/55056092)�С�

NS(���������)���ܻ��ڵ�������֡�а������ LinkAdrReq ����ն�Ϊ������ channel mask �����ᰴ��������Ϣ�е�������˳����һ�ش������е� LinkAdrReq ��Ϣ�� �ն˿��ܻ���ջ��߾ܾ������������ channel mask �Ŀ��ƣ������ LinkAdrAns ����������������� Channel Mask ACK ״̬����ָʾ��Ӧ�� channel mask ������� �ն������������ʱֻ�������һ����Ϣ�е� DataRate, TXPower �� NbTrans �ֶΡ��ն���Ҫ��ÿһ�� LinkAdrAns ���������� ACK ״̬����ָʾ����Щ�������õĽ������


�ŵ�Ƶ����Ϣ�ǰ������涨���ڵ�6�����ж��塣�ն�ʹ�� LinkADRAns ������Ӧ�� LinkADRReq ����ն�Ϊ������

<table>
   <tr>
      <td><b>Size (bytes)</b></td>   
      <td>1</td>   
   </tr>
   <tr>
      <td><b>LinkADRAns Payload</b></td>
      <td>Status</td>
   </tr>
</table>


<table>
   <tr>
      <td><b>Bits</b></td>   
      <td>[7:3]</td>   
	  <td>2</td>  
	  <td>1</td>  
	  <td>0</td>  
   </tr>
   <tr>
      <td><b>Status bits</b></td>
      <td>RFU</td>
	  <td>Power ACK</td>
	  <td>Data rate ACK</td>
	  <td>Channel mask ACK</td>
   </tr>
</table>

LinkADRAns �� Status λ�������¶��壺

<table>
   <tr>
      <td><b> /b></td>   
      <td><b>Bit = 0</b></td> 
	  <td><b>Bit = 1</b></td> 
   </tr>
   <tr>
      <td><b>Channel mask ACK</b></td>
      <td>������ channel mask ʹ����δ������ŵ����߽����������ŵ�������������ն�״̬���䡣</td>
	  <td>������ channel mask �ѳɹ��������Ѱ��� mask �����˵�ǰ���ŵ�״̬��</td>
   </tr>
   <tr>
      <td><b>Data rate ACK</b></td>
      <td>��������������ʣ��ն��޷�ʶ�𣬻����޷�Ӧ���ڵ�ǰ�ŵ��С�����������ն�״̬���䡣</td>
	  <td>�������ʳɹ����á�</td>
   </tr>
   <tr>
      <td><b>Power ACK</b></td>
      <td>������ķ��书�ʲ������ն���ִ�С�����������ն�״̬���䡣</td>
	  <td>���ʵȼ��ɹ����á�</td>
   </tr>
</table>

���������λ�����κ�һλ����0��������û�гɹ����ڵ㱣��֮ǰ��״̬��

## <a name="5.3">5.3 �ն˷���ռ�ձ�(DutyCycleReq, DutyCycleAns)</a>

## <a name="5.4">5.4 ���մ��ڲ���(RXParamSetupReq,RXParamSetupAns)</a>


## <a name="5.5">5.5 �ն�״̬(DevStatusReq, DevStatusAns)</a>

ͨ�� DevStatusReq ���NS(���������)���Ի�ȡ�ն˵�״̬��Ϣ�����������غɡ�һ���ն��յ� DevStatusReq ������ظ� DevStatusAns ���

<table>
   <tr>
      <td><b>Size (bytes)</b></td>   
      <td>1</td>   
   </tr>
   <tr>
      <td><b>LinkADRAns Payload</b></td>
      <td>Status</td>
   </tr>
</table>


<table>
   <tr>
      <td><b>Bits</b></td>   
      <td>[7:3]</td>   
	  <td>2</td>  
	  <td>1</td>  
	  <td>0</td>  
   </tr>
   <tr>
      <td><b>Status bits</b></td>
      <td>RFU</td>
	  <td>Power ACK</td>
	  <td>Data rate ACK</td>
	  <td>Channel mask ACK</td>
   </tr>
</table>



## <a name="5.6">5.6 �ŵ��Ĵ������޸�(NewChannelReq, NewChannelAns, DlChannelReq, DlChannelAns)</a>

## <a name="5.7">5.7 TX �� RX ֮�����ʱ����(RXTimingSetupReq, RXTimingSetupAns)</a>

## <a name="5.8">5.8 �ն˷��Ͳ���(TxParamSetupReq, TxParamSetupAns)</a>

---
δ�������

