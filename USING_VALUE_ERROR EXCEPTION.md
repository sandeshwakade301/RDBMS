DECLARE

&nbsp;      

&nbsp;   a number(2);

&nbsp;   b number(2);

&nbsp;   ans number(2);



BEGIN

&nbsp;   

&nbsp;     a:=\&a;

&nbsp;     b:=\&b;

&nbsp;     ans:=a+b;



&nbsp;     dbms\_output.put\_line('addition='||ans);



exception



&nbsp;     when value\_error then



&nbsp;       dbms\_output.put\_line('error');

end;

/      

