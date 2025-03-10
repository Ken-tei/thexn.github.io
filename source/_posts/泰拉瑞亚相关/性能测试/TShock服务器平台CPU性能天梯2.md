---
title: TShock������ƽ̨CPU��������ͼ
tags: [̩������,Terraria,TShock]
categories:
  - [̩������,TShock]
date: 2024-10-23 15:41:54
sticky: 97
---

<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TShock������ƽ̨CPU��������ͼ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }

        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        th,
        td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        .details {
            display: none;
            text-align: left;
            margin-top: 10px;
        }

            .details img {
                max-width: 150px;
                height: auto;
                margin-right: 20px;
                vertical-align: middle;
            }
    </style>
    <script>function toggleDetails(id) {
            const details = document.getElementById(id);
            details.style.display = details.style.display === 'none' ? 'block' : 'none';
        }</script>
</head>

<body>
    <header>
        <h1>CPU ��������ͼ</h1>
    </header>
    <h2>ǰ��</h2>
    <p>���Է�ʽ����Ϊ������ң���ҹ���ԣ���ҽ������ִ�м���ָ�10���ִ��5��ָ��Ҽ�¼����������Ϊ���ѡ���ͼ��1000000�����������±�ʱ�䣬���������˱�������ͼ�浵������Ⱦ���ͬ��</p>
    <table>
        <thead>
            <tr>
                <th>CPU �ͺ�</th>
                <th>���ܷ���</th>
                <th>����</th>
            </tr>
        </thead>
        <tbody>
            <!-- 1 -->
            <tr>
                <td>��û� R9-9900X 9950X</td>
                <td>1249229.490</td>
                <td><button onclick="toggleDetails('details1')">չ��</button></td>
            </tr>
            <tr id="details1" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� R9-9900X 9950X.jpg" alt="��û� R9-9900X 9950X">
                    S��R9-9900X/9950X��.A.M.L 4��8g 25G��Ӳ�̣�170����
                </td>
            </tr>

            <tr>
                <td>��û� R9-7900X 7950X</td>
                <td>1137226.23</td>
                <td><button onclick="toggleDetails('details4')">չ��</button></td>
            </tr>
            <tr id="details4" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� R9-7900X 7950X.jpg" alt="��û� R9-7900X 7950X">
                    S-��R9-7900X/7950X��.A.M.L 4��8g 25G��Ӳ�̣�145����
                </td>
            </tr>

            <tr>
                <td>��û� I9-13900K, I7-14700K</td>
                <td>1095073.400</td>
                <td><button onclick="toggleDetails('details2')">չ��</button></td>
            </tr>
            <tr id="details2" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� I9-13900K, I7-14700K.jpg" alt="��û� I9-13900K, I7-14700K">
                    S��I9-13900K,I7-14700K��.I.M.L 4��8g 25G��Ӳ�̣�170����
                </td>
            </tr>


            <tr>
                <td>Loguhan�� AMD Ryzen 5 5500</td>
                <td>945001.978</td>
                <td><button onclick="toggleDetails('details20')">չ��</button></td>
            </tr>
            <tr id="details20" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/Loguhan�� AMD Ryzen 5 5500.png" alt="Loguhan�� AMD Ryzen 5 5500">
                    Loguhan�� AMD Ryzen 5 5500
                </td>
            </tr>

            <tr>
                <td>��û� I7-12700K,I7-13700K</td>
                <td>939637.550</td>
                <td><button onclick="toggleDetails('details3')">չ��</button></td>
            </tr>
            <tr id="details3" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� I7-12700K,I7-13700K.jpg" alt="��û� I7-12700K,I7-13700K">
                    S-��I7-12700K,I7-13700K��.I.M.L 4��8g 25G��Ӳ�̣�145����
                </td>
            </tr>

            <tr>
                <td>��û� R9-5900X, R9-5950X</td>
                <td>829916.660</td>
                <td><button onclick="toggleDetails('details5')">չ��</button></td>
            </tr>
            <tr id="details5" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� R9-5900X, R9-5950X.jpg" alt="��û� R9-5900X, R9-5950X">
                    A��R9-5900X/5950X��.A.M.L 4��8g 20G��Ӳ�̣�130����
                </td>
            </tr>
            <!-- 6 -->
            <tr>
                <td>��ѧ R7-4800H</td>
                <td>839295.236</td>
                <td><button onclick="toggleDetails('details6')">չ��</button></td>
            </tr>
            <tr id="details6" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��ѧ R7-4800H.jpg" alt="��ѧ R7-4800H">
                    ��ѧ���ĵ���
                </td>
            </tr>
            <!-- 7 -->
            <tr>
                <td>���� R7-5700U</td>
                <td>715876.960</td>
                <td><button onclick="toggleDetails('details7')">չ��</button></td>
            </tr>
            <tr id="details7" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/���� R7-5700U.jpg" alt="���� R7-5700U">
                    ���Լ��ĵ���
                </td>
            </tr>

            <tr>
                <td>��Ѷ�� AMD EPYC 7K62 48-Core Processor 2.60 GHz</td>
                <td>585560.768</td>
                <td><button onclick="toggleDetails('details18')">չ��</button></td>
            </tr>
            <tr id="details18" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��Ѷ�� AMD EPYC 7K62 48-Core Processor 2.60 GHz.jpg" alt="��Ѷ�� AMD EPYC 7K62 48-Core Processor 2.60 GHz.jpg">
                    ��Ѷ���ػݻ��� ���Ǽ���3����
                </td>
            </tr>

            <tr>
                <td>��û� EPYC 7C13, EPYC 7B13, EPYC 7713</td>
                <td>585560.768</td>
                <td><button onclick="toggleDetails('details8')">չ��</button></td>
            </tr>
            <tr id="details8" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� EPYC 7C13, EPYC 7B13, EPYC 7713.jpg" alt="��û� EPYC 7C13, EPYC 7B13, EPYC 7713">
                    B+��EPYC 7C13/7B13/7713��.A.L.L 4��16g 16G��Ӳ�̣�85����
                </td>
            </tr>
            <!-- 9 -->
            <tr>
                <td>���� E5-2666v3</td>
                <td>557747.384</td>
                <td><button onclick="toggleDetails('details9')">չ��</button></td>
            </tr>
            <tr id="details9" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/���� E5-2666v3.jpg" alt="���� E5-2666v3">
                    ÿ��ǩ��500���֣��򵥵�һ���Ի��ֹ�8000��2000������ȡ7�죬�������7��2258
                    ���� E5-2666v3 ��̬�Ʒѣ��������е�������2 vCPU 4 GB 10 GB�����̣�20 Mbps 100 Mbps�����£�
                    ���˲������� �������������Զ��������ű����о������������� ��ʦFTW������1��7���������������1000�������ң����ڻ���500�������һ������ֵ����⣬���Է������� �����ʱ���Ī�����������Ǻ�̨δ��ʾ��ұ��߳����ֶ��߳��󣬴󲿷����Ҳ�޷��ٴν��룬���Һ�̨û����ҵ����������ڼ�û����Բ�������������������������Ƶ�����
                </td>
            </tr>

            <tr>
                <td>Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz</td>
                <td>506865.884</td>
                <td><button onclick="toggleDetails('details17')">չ��</button></td>
            </tr>
            <tr id="details17" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz.jpg" alt="Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz">
                    ����S4
                </td>
            </tr>

            <tr>
                <td>��û� E5-2690v4,����8175M,����6148</td>
                <td>505349.168</td>
                <td><button onclick="toggleDetails('details15')">չ��</button></td>
            </tr>
            <tr id="details15" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� E5-2690v4,����8175M,����6148.jpg" alt="��û� E5-2690v4,����8175M,����6148">
                    B-��E5-2690v4,����8175M,����6148��.I.M+.L 4��12g 16G��Ӳ�̣�60����
                </td>
            </tr>

            <tr>
                <td>��û� E5-2682v4</td>
                <td>454498.988</td>
                <td><button onclick="toggleDetails('details11')">չ��</button></td>
            </tr>
            <tr id="details11" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� E5-2682v4.jpg" alt="��û� E5-2682v4">
                    C+��E5-2682v4��.I.M+.L 4��12g 16G��Ӳ�̣�50����
                </td>
            </tr>

            <tr>
                <td>��û� E5-2696v2, E5-2697v2</td>
                <td>393140.364</td>
                <td><button onclick="toggleDetails('details10')">չ��</button></td>
            </tr>
            <tr id="details10" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� E5-2696v2, E5-2697v2.jpg" alt="E5-2696v2">
                    C��E5-2696v2��E5-2697v2��.I.L.L 4��16G 16G��Ӳ�̣���50����
                </td>
            </tr>


            <tr>
                <td>wemc δ֪����</td>
                <td>344878.558</td>
                <td><button onclick="toggleDetails('details16')">չ��</button></td>
            </tr>
            <tr id="details16" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/wemc δ֪����.jpg" alt="wemc δ֪����">
                    ����ʹ�����飺������ֵ�С���⣬�������ǵ������ű�̫���ˣ��������Զ��������ű����㲻���������ǵĽű���
                </td>
            </tr>

            <tr>
                <td>��û� ����8151</td>
                <td>288840.012</td>
                <td><button onclick="toggleDetails('details12')">չ��</button></td>
            </tr>
            <tr id="details12" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� ����8151.jpg" alt="��û� ����8151">
                    B++������8151��.I.L.L4��16g 20G��Ӳ�̣�95����
                </td>
            </tr>

            <tr>
                <td>��û� ����6140</td>
                <td>199229.238</td>
                <td><button onclick="toggleDetails('details13')">չ��</button></td>
            </tr>
            <tr id="details13" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� ����6140.jpg" alt="��û� ����6140">
                    C++������6140��.I.M.L 4��8G 16G��Ӳ�̣���50����
                </td>
            </tr>

            <tr>
                <td>��û� ����8124 8124M</td>
                <td>197233.306</td>
                <td><button onclick="toggleDetails('details14')">չ��</button></td>
            </tr>
            <tr id="details14" class="details">
                <td colspan="4">
                    <img src="TShock������ƽ̨CPU��������/��û� ����8124 8124M.jpg" alt="��û� ����8124 8124M">
                    B������8124/8124M��.I.M.L 4��8g 16G��Ӳ�̣�70����
                </td>
            </tr>
        </tbody>
    </table>
</body>

</html>