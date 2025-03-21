# Answers.sql
CREATE DATABASE SalesDB;
USE SalesDB;
CREATE TABLE stocks (TradeDATE CHAR(10),
                     SPY double,
                     GLD double,
                     AMZN double,
                     KPTI double,
                     GILD double,
                     MPC double,
SELECT * FROM stocks;
INSERT INTO stocks VALUES(),

TradeDATE	SPY	GLD	AMZN	GOOG	KPTI	GLD	MPC
1/1/2025	0.002	1.678	0.738	0.463	0.356	0.345	0.234
3/3/2025	0.045	1.6778	0.378	0.573	0.3765	1.2345	0.346
4/3/2025	0.467	0.679	0.564	0.355	0.2567	1.456	1.345
6/3/2025	0.156	0.976	0.098	0.927	0.208	0.0982	0.2876
9/4/2025	0.357	0.377	0.279	0.276	0.287	0.028	0.286
![image](https://github.com/user-attachments/assets/0284e291-53ef-4c02-9ea0-541cf520f14e)
UPDATE stocks SET TradeDATE = str_to_date(TradeDATE, {"%m%d%Y");

