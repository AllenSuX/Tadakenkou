<template>
    <h1 class="pt-3 pb-1m-0">
        会社概要
    </h1>
    <span class="p-0 m-0">
        Company profile
    </span>
    <div class="container-fluid mt-2">
        <div class="row justify-content-around m-0">
            <table class="col-12 col-lg-5">
                <tbody>
                    <tr>
                        <th class="first-td">
                            名称
                        </th>
                        <td class="first-td">
                            ターダ建工
                        </td>
                    </tr>
                    <tr>
                        <th>所在地</th>
                        <td>
                            〒940-0016<br>
                            新潟県長岡市宝３丁目４−２２
                        </td>
                    </tr>
                    <tr>
                        <th>
                            代表取締役
                        </th>
                        <td>
                            多田　一夫
                        </td>
                    </tr>
                    <tr>
                        <th>
                            従業員数
                        </th>
                        <td>
                            6名
                        </td>
                    </tr>
                    <tr>
                        <th>
                            特徴
                        </th>
                        <td>
                            建築関連全般から産業機器、SUS製品等精密板金加工を主力としております。
                            <br>
                            レーザ加工機・複合機・タレパンとの設備を生かし製品への品質向上を追及し提案型な会社です。
                        </td>
                    </tr>
                    <tr>
                        <th>
                            製品形状
                        </th>
                        <td>
                            パネル・ドア・カバー・ケース、
                            シャーシ・ベース・フレーム、
                            精密部品・機構部品・内部部品、
                            リブ・ブラケット・小物部品、
                            サッシ・長尺・大物、厚板・製缶
                        </td>
                    </tr>
                    <tr>
                        <th>
                            物作りの範囲
                        </th>
                        <td>
                            設計、プログラム、板金加工、機械加工、溶接、表面処理、各種装置
                        </td>
                    </tr>
                </tbody>
            </table>
            <table class="col-12 col-lg-5">
                <tbody>
                    <tr>
                        <th class="first-td borderOff">
                            加工内容
                        </th>
                        <td class="first-td borderOff ">
                            素材切断から溶接組立。
                            レーザ切断・タレパン加工。
                            薄板～厚板までの加工可能。
                        </td>
                    </tr>
                    <tr>
                        <th>
                            取扱材料・材質
                        </th>
                        <td>
                            SPC、SS400、SUS、AL、銅
                        </td>
                    </tr>
                    <tr>
                        <th>
                            製品分野
                        </th>
                        <td>
                            ロッカー・スチール家具、鉄骨・建設金属、サッシ・建設金属、厨房料理装置、
                            空調冷暖房機器、業務用冷凍ショーケース、看板装飾照明インテリア、
                            建築物、建造物、産業・特殊機械装置、工作機械・カバー類、農業用機械、
                            自販機・自動サービス機、エレベータ・昇降機、タイプ・レジ・事務機器、
                            工具・機械刃物、ミシン・編機、発電・電動機・変圧器、配電盤・制御盤、
                            家電・照明器具、テレビ・音響・ビデオ機器、OA・FA・コンピュータ機器、
                            通信・無線・応用機器、乗用車・車体・内外装、トラック・特殊車両、
                            自動車部品・伝送照明、オートバイ、自転車、鉄道・保全信号、航空機、
                            医療機器・X線、測定器・試験機、電気計測・アナライザ、測定器具・メーター類、
                            理化学・分析器具、玩具・ゲーム類、楽器、雑貨・ボルト・金物
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
       
      
    </div>
</template>
<style scoped>
    h1{
        font-family: "游明朝", HiraMinProN-W3, "ヒラギノ明朝 Pro W3" ,"Hiragino Mincho Pro","ＭＳ Ｐ明朝", "MS PMincho", serif;
        font-weight: bold;
        line-height: 1;
        text-align: center;
    }
    span{
        display: block;
        margin-top: 0.5rem;
        font-size: 1.2rem;
        color: #003690;
        text-align: center;
    }
    .inner table{
        width: 48%;
        border-collapse: collapse;
        border-spacing: 0;
    }
    tbody{
        vertical-align: text-top;
    }
    th{
        width:20%;
    } 
    tr:first-child th,td{
        border-top: 1px solid lightgray;
    }
    td{
        padding: 1rem;
        border-bottom: 1px solid lightgray;
        
    }
    tr{
        border-bottom: 1px solid lightgray;
    }
    /* .first-td{
        border-top: 1px solid lightgray;
    } */
    @media screen and (max-width: 768px) {
        tr,th,td {
            display: block;
            width: 100%;
        }
        td{
            border-bottom: 0;
        }
    }
</style>