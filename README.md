# TopFreeProxies
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alanbobs999/topfreeproxies/sub_merge?label=sub_merge)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/sub_merge.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如果有需要可以自行 Fork 实现个性化需求。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity.yml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `100`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDktdW5pdnN0YXIiLCJhZGQiOiIxNDMuMTk4LjEzMC4yMSIsInBvcnQiOiI0MjM4MiIsInR5cGUiOiJub25lIiwiaWQiOiIwM2I0NTJhNy05MDdiLTRmNzctOGNhNC02MDI1MGNjODM1YmMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1#US%2060-univstar
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#US%2053-univstar
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#US%2055-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDctdW5pdnN0YXIiLCJhZGQiOiIxNTAuMjMwLjQxLjkiLCJwb3J0IjoiMjMyOTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTU2YzZjMmYtYmY1NC00Yjg3LWZhZmQtNGI3NjdjYTEyNzUwIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjM0LjIxNS4xMzAuMTg2IiwidGxzIjoiIn0=
    trojan://sharecentre@ussc.scsevers.cf:443?allowInsecure=1#US%2059-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDgtdW5pdnN0YXIiLCJhZGQiOiIxNTAuMjMwLjQzLjEwNiIsInBvcnQiOiI1NDgyOSIsInR5cGUiOiJub25lIiwiaWQiOiJmMmI1YzNmZi04NmM3LTRlZmEtODMxZi1mZjBmY2Q3NjU2YTUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTAtdW5pdnN0YXIiLCJhZGQiOiIxNTUuMjQ4LjIwMi4yMDMiLCJwb3J0IjoiMTQ1NjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGEwZGEzNzktYTdjYy00Mzg5LTg4ZDctNDU1MTRiODk2ODgzIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=1#US%2056-univstar
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-us01.yiyodns.xyz:443?allowInsecure=1#US%2062-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDEtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzgtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzYtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxNTIuNjkuMTk5LjExMSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzEtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMzYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjctdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDAtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMzUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjktdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjQtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxNTIuNjkuMTk5LjExMSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzMtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTQiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDMtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuOCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxNTIuNjkuMTk5LjExMSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjMtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjYtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzktdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzctdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMzAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTQtdW5pdnN0YXIiLCJhZGQiOiIxNjguMTM4LjIwOC4xNDUiLCJwb3J0IjoiNTY4MTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiODZhY2ExOWYtZDIzYi00ZjA4LTk2NzctYTA2MWI3MjgyYmI5IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzItdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzAtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzQtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMzEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    trojan://a580d839-ee41-4df1-bf03-6789dca32e30@jgwdb1.gaox.ml:443?allowInsecure=1&sni=jgwdb1.gaox.ml#AU%202-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMzUtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTYiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjgtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMTUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    trojan://8d2d5953-d649-4034-94f2-72f2df2623da@jgwdb3.gaox.ml:443?allowInsecure=1#US%2064-univstar
    trojan://48ac743a-2d49-4191-b804-0c7fa7e01146@mc.vpshax.ml:443?allowInsecure=1#US%2057-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNTAtdW5pdnN0YXIiLCJhZGQiOiIyMC4xMjMuMTg3LjIxMiIsInBvcnQiOiIyNzkzMSIsInR5cGUiOiJub25lIiwiaWQiOiIyNTZlYWU0MS0wYjhmLTRmYWEtYmNlOC02MzY2MDExZGMxOWYiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    trojan://02e653c9-7c93-46a9-999d-11834bd0c577@jgwld1.gaox.ml:443?allowInsecure=1#GB%202-univstar
    trojan://d7fd8aaa-4581-4281-80aa-4b63e5e1f157@jgwld2.gaox.ml:443?allowInsecure=1#GB%201-univstar
    trojan://58d32c66-43b1-4561-9951-d87c9123774e@jgwld4.gaox.ml:443?allowInsecure=1#US%2073-univstar
    trojan://9eef43d9-712e-4850-bb7a-12b279a96de5@kk.2046.gq:4443?allowInsecure=1&sni=kk.2046.gq#AU%203-univstar
    trojan://3a2c0c6c-9ee5-c05f-c951-fcd73831983e@kr05.wangxd.life:3052?allowInsecure=1#US%2067-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNTItdW5pdnN0YXIiLCJhZGQiOiIxNTIuNzAuMjM0LjcwIiwicG9ydCI6IjI2NzAxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjA1ZjgyNGYzLTQ3MjQtNDM0NC1iMjZiLTllZGQ2MDI4NzRiYiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIzNC4yMTUuMTMwLjE4NiIsInRscyI6IiJ9
    trojan://7118b5f4-0ea4-4c11-be7f-11471cb91e4a@jgwcc1.gaox.ml:443?allowInsecure=1#GB%203-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTYtdW5pdnN0YXIiLCJhZGQiOiIxNTAuMjMwLjIwOS4xMzgiLCJwb3J0IjoiMTg3NTIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzA2ODExNTAtNGIyMi00ODA5LTlmZDktMmZlMjg5YTljZDlmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTUtdW5pdnN0YXIiLCJhZGQiOiIxMzguMi4xNS4yMyIsInBvcnQiOiI0NjM3MCIsInR5cGUiOiJub25lIiwiaWQiOiI5OTgxNTFlNS0wYmM1LTQzNzctZTM5MC1jNDFiYjI2ZmRkMGMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDItdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxNTIuNjkuMTk5LjExMSIsInRscyI6IiJ9
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-hk01.yiyodns.xyz:443?allowInsecure=1#HK%205-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNTEtdW5pdnN0YXIiLCJhZGQiOiIyMy45NC4xMjAuMTkiLCJwb3J0IjoiMjg1NTQiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGE0Yzk2YzUtN2I4Yi00NjEyLWM3MTUtNmI5MWE5YzM0ZDA3IiwiYWlkIjoiNjQiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIzNC4yMTUuMTMwLjE4NiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDUtdW5pdnN0YXIiLCJhZGQiOiIzNC4yMTUuMTMwLjE4NiIsInBvcnQiOiIxMDA4OSIsInR5cGUiOiJub25lIiwiaWQiOiIzNjA4YzlkYy0xZWViLTQ4YjAtYjU3MC00MzA3NGI0YTBjOWUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIzNC4yMTUuMTMwLjE4NiIsInRscyI6IiJ9
    trojan://c2b60d6a-a2f5-40ff-b7f9-f7658abcbf26@jgwxn2.gaox.ml:443?allowInsecure=1#AU%204-univstar
    trojan://cb43b7c2-b744-41c5-bcc2-fd7467b332cf@jgwxn3.gaox.ml:443?allowInsecure=1#AU%206-univstar
    trojan://sharecentre@sg.sharecentrepro.tk:443?allowInsecure=1#SG%207-univstar
    trojan://affae2e0-e84b-11ec-b09f-1239d0255272@trojan1.udpgw.com:443?allowInsecure=1#SG%203-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTctdW5pdnN0YXIiLCJhZGQiOiIxNTAuMjMwLjk5LjQ2IiwicG9ydCI6IjIyMjIyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImU2YzU1ZDM2LTAyMmMtNGViYy1iOWMyLWUxMjIwYTcxODRmNCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiU0cgNi11bml2c3RhciIsImFkZCI6IjgxLjkwLjE4OC41OSIsInBvcnQiOiI0MTY1NyIsInR5cGUiOiJub25lIiwiaWQiOiI5MzBhNDI1ZS0yZmM4LTQ5MzAtODczNS0xNDFmNmIyMzc3NTUiLCJhaWQiOiI2NCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTktdW5pdnN0YXIiLCJhZGQiOiIxMzguMi4zOC40NiIsInBvcnQiOiIyNTU2NSIsInR5cGUiOiJub25lIiwiaWQiOiI0OWExZjg3ZS1hYmY5LTQxODAtODcwMC03MmZlNTAyZjNmYWUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVFcgMy11bml2c3RhciIsImFkZCI6IjYxLjIyMi4yMDIuMTQwIiwicG9ydCI6IjE1Nzg5IiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ1MzVlNzA4LTU5ODgtNDM3Ny1hMDgzLTc1NWVkNjBkODA2OCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://54080134-2cba-4535-8599-95650bd9aa54@jgwhdlb2.gaox.ml:443?allowInsecure=1#US%2070-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMTgtdW5pdnN0YXIiLCJhZGQiOiIxNTAuMjMwLjQuMTM2IiwicG9ydCI6IjExMTUxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE4ZWY4Yjg2LTVkZmUtNDhhOS1iNGU0LWI1ZjU5NWY3ZTU1NSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://006baa3f-4bc3-4915-b60d-c8c5dae11a11@jgwhdlb3.gaox.ml:443?allowInsecure=1#US%2013-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiUlUgMS11bml2c3RhciIsImFkZCI6IjE5NC44Ny45OS4xMjIiLCJwb3J0IjoiMjMxNjUiLCJ0eXBlIjoibm9uZSIsImlkIjoiZTE5YzAzZjYtOTdiOS00YzJiLWE0MmQtMTlkYWVhMThkODQ5IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMjUtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjUiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiQVUgMS11bml2c3RhciIsImFkZCI6IjEyOS4xNTQuNDguMjIxIiwicG9ydCI6IjM3MzcyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjZmNDQ1NGE5LWU3MzItNDZjNi1jNTBmLTczZjEzZGEzMWY3YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIzNC4yMTUuMTMwLjE4NiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiREUgMS11bml2c3RhciIsImFkZCI6IjUuMTgzLjMyLjE4NyIsInBvcnQiOiIzMjE2OSIsInR5cGUiOiJub25lIiwiaWQiOiI0NmEyZjQ2YS1jNTZmLTQ4N2ItYjJjOS1iNDIwNGJmODAyMWUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    trojan://5HfENR8nt2PR8reH@rooms.starspace.link:443?allowInsecure=1#US%2061-univstar
    trojan://151dada5-c12e-4eb3-940e-d93f365f8a4a@198.200.51.219:26969?allowInsecure=1#US%2065-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVFcgMi11bml2c3RhciIsImFkZCI6IjYxLjIyMi4yMDIuMTQwIiwicG9ydCI6IjMzNzkyIiwidHlwZSI6Im5vbmUiLCJpZCI6ImU1NWNkMTgyLTAxYjAtNGZiNy1hNTEwLTM2MzcwMWE0OTFjNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjYxLjIyMi4yMDIuMTQwIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEsgNC11bml2c3RhciIsImFkZCI6IjExOS4yOC45Mi4xMjUiLCJwb3J0IjoiNzY1NCIsInR5cGUiOiJub25lIiwiaWQiOiI5NDgxZTUyNS01NTdiLTQ4NWQtOGI2NC1lYzE0MjcwOTc0ZDIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiU0cgOS11bml2c3RhciIsImFkZCI6IjguMjEwLjEyNy4yMTQiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjViMDBiZDM0LWEyYTctNDQ3MS04YjE3LTNmNDc2OGFjMDMzMCIsImFpZCI6IjY0IiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://ZD4dLSBXiMrmzdLd@v2cross.com.03.v2ce.com:443?allowInsecure=1#UA%202-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiU0cgNS11bml2c3RhciIsImFkZCI6IjEyOS4yMjYuODkuNzciLCJwb3J0IjoiMTM3NTMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTgzYjI0Y2UtMjViOC00ZjE2LWMwMzMtOTYyOWQ0OGJlMzcyIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSlAgMS11bml2c3RhciIsImFkZCI6IjQzLjE1NC4xMTQuMjA4IiwicG9ydCI6IjMyNDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiZTRhMTViMWQtOGRmZC00YmQ3LWFiMzMtMDZjOGNkMTc0YzBiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjM0LjIxNS4xMzAuMTg2IiwidGxzIjoiIn0=
    trojan://c9a3a61d-5d49-4158-9e60-6fa32684b122@cm.spacez.cloud:30003?allowInsecure=1#CN%204-univstar
    trojan://5y8y3CwxRVYhyfSY@ce.rutracker-cn.com:443?allowInsecure=1#UA%204-univstar
    trojan://kGrwqmB1nEKUsDwE@v2cross.com.05.v2ce.com:443?allowInsecure=1#UA%201-univstar
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-us02.yiyodns.xyz:443?allowInsecure=1#US%202-univstar
    trojan://W8gVbKNAZlFzgGPn@storage.starspace.link:443?allowInsecure=1#US%2012-univstar
    trojan://3gLlCYBipVwr6Y5F@v2cross.com.02.v2ce.com:443?allowInsecure=1#CZ%201-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDQtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuMjAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMwMTU2NDUxLTRlZmItNDVlMi04NGZjLThkMzE1YzQ2NTBkYiIsImFpZCI6IjMyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUyLjY5LjE5OS4xMTEiLCJ0bHMiOiIifQ==
    trojan://mMQ6qJB9xbhiRvgg@v2cross.com.01.v2ce.com:443?allowInsecure=1#CZ%202-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNDYtdW5pdnN0YXIiLCJhZGQiOiI1MS44MS4yMjMuNiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIzNC4yMTUuMTMwLjE4NiIsInRscyI6IiJ9
    trojan://HTrovQkamDxNfaD5@cz5.v2ce.com:443?allowInsecure=1#UA%206-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgNS11bml2c3RhciIsImFkZCI6IjUxLjgxLjIyMy4xOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMgMS11bml2c3RhciIsImFkZCI6IjUxLjgxLjIyMy4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzAxNTY0NTEtNGVmYi00NWUyLTg0ZmMtOGQzMTVjNDY1MGRiIiwiYWlkIjoiMzIiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1#US%2069-univstar
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-hk02.yiyodns.xyz:443?allowInsecure=1#HK%206-univstar
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s4.hazz.win:12340?allowInsecure=1#DE%202-univstar
    trojan://vGWCNNfBHwSY6m6M@v2cross.com.04.v2ce.com:443?allowInsecure=1#UA%205-univstar
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s2.hazz.win:12340?allowInsecure=1#SG%208-univstar
    trojan://4ZPDeqJ6g766UKDJ@silicon.starspace.link:443?allowInsecure=1#US%2011-univstar
    trojan://f64e69c0-e7b7-11ec-ab81-1239d0255272@w11.udpgw.com:443?allowInsecure=1#SG%204-univstar
    trojan://7dafe71e-2be6-302f-bdfc-e6319a3299bc@tj-sg02.yiyodns.xyz:443?allowInsecure=1#US%207-univstar
    trojan://16877c70-e7b8-11ec-99f2-1239d0255272@w13.udpgw.com:443?allowInsecure=1#SG%202-univstar
    trojan://7497242f-3044-3c77-bf48-14bb26c92a83@azgy001.xiba1.xyz:20711?allowInsecure=1&sni=ssl.ssl12.xyz#HK%207-univstar
    trojan://7497242f-3044-3c77-bf48-14bb26c92a83@azgy001.xiba1.xyz:20710?allowInsecure=1&sni=ssl.ssl12.xyz#HK%208-univstar
    ss://YWVzLTI1Ni1nY206NmY4ZWJlODMtODkxMC00MTA2LTlkYzQtMThhNDFjYzIwZWQ0@zh01lv3sgp01.feiguayun.xyz:50031#CN%201-univstar
    trojan://s6rIg1Mkke73fwZU@tw-oo-01.click:443?allowInsecure=1#TW%201-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiS1IgMi11bml2c3RhciIsImFkZCI6IjAwMDEua3IuZ2VuenBuLmNvbSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI0ZjQ0MThjZC0zODVjLTQyMDMtYTMyMy0xYjRkMmJlOGU0OTUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIwMDAxLmtyLmdlbnpwbi5jb20iLCJ0bHMiOiIifQ==
    trojan://4f4418cd-385c-4203-a323-1b4d2be8e495@0001.kr.genzpn.com:443?allowInsecure=1#KR%201-univstar
    trojan://s6rIg1Mkke73fwZU@zq-vip-09.com:443?allowInsecure=1&sni=zq-vip-09.com#TW%204-univstar
    vmess://eyJ2IjoiMiIsInBzIjoiTU4gMS11bml2c3RhciIsImFkZCI6IjE4Mi4xNjAuMTIuMjM5IiwicG9ydCI6IjQ1NTI0IiwidHlwZSI6Im5vbmUiLCJpZCI6ImEyNjVkY2IyLTA0YTMtNDhjMC1hNzAzLWZhZDBlMDA4ZDQ3NCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJjZG4ucWNod25kLm1vZSIsInRscyI6IiJ9
    trojan://08964210-e7b8-11ec-95aa-1239d0255272@w12.udpgw.com:443?allowInsecure=1#SG%201-univstar

</details>

### 所有节点
合并节点总数: `13270`
[节点链接](https://raw.githubusercontent.com/reny311/proxyTop/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `88`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `427`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `126`
- [freefq/free](https://github.com/freefq/free), 节点数量: `41`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `137`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `75`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `121`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `3440`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `130`
- [iwxf/free-v2ray](https://github.com/iwxf/free-v2ray), 节点数量: `8`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `42`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `33`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `145`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `41`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `56`
- [ObcbO/auto-subscribe](https://github.com/ObcbO/auto-subscribe), 节点数量: `0`
- [Jinxnet 节点池](https://pool.jinxnet.xyz), 节点数量: `0`
- [tomdegnan/clashrule](https://github.com/tomdegnan/clashrule), 节点数量: `214`
- [TG@getv2ray](https://t.me/getv2ray), 节点数量: `0`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `33`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `236`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `41`
- [KYLELI1991/sysucc](https://github.com/KYLELI1991/sysucc), 节点数量: `0`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `27`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `46`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `115`
- [poduv/poduv](https://github.com/poduv/poduv), 节点数量: `88`
- [ok1991/v2ray](https://github.com/ok1991/v2ray), 节点数量: `39`
- [parkerpa/jsfxs](https://github.com/parkerpa/jsfxs), 节点数量: `582`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `38`
- [songkaik/Sub](https://github.com/songkaik/Sub), 节点数量: `0`
- [yosefwang/subscription](https://github.com/yosefwang/subscription), 节点数量: `0`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `101`
- [my](https://github.com/reny311), 节点数量: `1052`
- [openit's proxy pool](open.ml), 节点数量: `4835`
- [jingfu](https://kingfu.herokuapp.com/), 节点数量: `432`
- [daycat](https://github.com/daycat/freeray/), 节点数量: `178`
- [univstar](https://t.me/univstar), 节点数量: `62`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 12¥200G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awslcn.xyz/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)
