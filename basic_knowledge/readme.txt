����BrowserSync �����ĺô��ǣ���д�߲���
1.��ȥ��װbrowserSync
   npm install browser-sync --save-dev
2. ����BrowserSync
browser-sync start --server --files "**/*.css, **/*.html"
=========================================
*����canvas����˳���

���Ʒ��飺
��fillRect(x,y,w,h)  Ĭ����ɫ�Ǻ�ɫ
��strokeRect(x,y,w,h); ���߿�ķ���
=========================================
������ʽ��
.fillStyle='red'  �����ɫ 
.lineWidth	�߿�
.strokeStyle   ��ߵ���ɫ
=========================================
�߽�����ʽ��
��lineJoin: �߽����ӵ����ʽ
	miter (Ĭ��) | round(Բ��) | bevel(б��)

.lineCap: �˵���ʽ  ��ʱ������Ч��
	butt(Ĭ��)  | round(Բ��) | square(�߶ȶ��Ϊ��һ���ֵ)

=========================================
����·��
beginPath : ��ʼ����·��
closePath : ��������·��
moveTo : �ƶ������Ƶ���Ŀ���
lineTo : �µ�Ŀ���
stroke : ���ߣ�Ĭ�Ϻ�ɫ
fill : ��䣬Ĭ�Ϻ�ɫ
rect : ��������
clearRect : ɾ��һ�������ľ�������
save : ����·��
restore : �ָ�·��
=========================================
����Բ�Σ�
	arc(x,y,r,��ʼ���ȣ��������ȣ���ת����)

������ǶȵĹ�ϵ��
	����=�Ƕ�*Math.PI/180
		

