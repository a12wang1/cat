DEMO
===========================

###########׼��
1. node v0.10.28+
2. Ganache�ͻ��ˣ��޸Ķ˿ں�Ϊ9545
3. �ȸ����������װMetaMask��������ӵ�http://127.0.0.1:9545
4. ��Ganache�ṩ�Ĳ����˻����뵽MetaMask��


###########������

1. ��sql�ļ��µ�sql�������ݿ���
2. ��modules/modelHead.js�޸�����ļ���Ϣ
3. npm install ��װ��ػ�������
4. truffle compilete 
5. truffle migrate --reset ��current block ��Ϊ0 ������ɹ���
6. npm start ������Ŀ


###########Ŀ¼�ṹ����
��  .project
��  app.js  //����ӿ�
��  asyncSeries.js
��  package-lock.json
��  package.json
��  README.md
��  truffle-box.json
��  truffle-config.js
��  truffle.js  //���޸����Ӷ˿�
��
����bin  
��      www  //��·��
��
����contracts  //��Լ
��      Coin.sol
��      Migrations.sol
��
����migrations
��      1_initial_migration.js
��      2_deploy_contracts.js
��
����modules  //���ݿ�����
��      modelHead.js
��
����public
��  ����images  // ͼƬ
��  ��      engine_1.jpg
��  ��      engine_2.jpg
��  ��      engine_3.jpg
��  ��      engine_4.jpg
��  ��      engine_5.jpg
��  ��      LED���.jpg
��  ��      power.jpg
��  ��      tyer_1.jpg
��  ��      tyer_2.jpg
��  ��      tyer_3.jpg
��  ��      ǰ��.jpg
��  ��      ѹ����.jpg
��  ��      ������_1.jpg
��  ��      ������_2.jpg
��  ��      ������.jpg
��  ��      ����.jpg
��  ��      ����.jpg
��  ��
��  ����javascripts  //JS 
��  ��      app.js
��  ��      bootstrap.min.js
��  ��      connect.js
��  ��      iziModal.min.js
��  ��      jquery-2.1.4.min.js
��  ��      jquery.min.js
��  ��      jquery.pagination.js
��  ��      purchase.js
��  ��      truffle-contract.js
��  ��      web3.min.js
��  ��
��  ����stylesheets  //CSS 
��          App.css
��          bootstrap.min.css
��          bootstrap.min.css.map
��          demo.css
��          iconfont.css
��          index.css
��          iziModal.css
��          open-sans.css
��          oswald.css
��          pure-min.css
��          style.css
��          style1.css
��
����routes  //��̨
��      users.js
��
����sql      //���ݿ�
��      shop_merchant.sql
��      shop_parts.sql
��      shop_routines.sql
��      shop_shops.sql
��
����test
��      .gitkeep
��      TestAdoption.sol
��
����views         //ҳ����·��
    ��  error.ejs
    ��
    ����index
            details.ejs  // ����ҳ��
            index.ejs   // ��ҳ
            purchase.ejs  //�����¼ҳ��
            success.ejs 
