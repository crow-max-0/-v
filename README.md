--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v62,v63) local v64={};for v82=1, #v62 do v6(v64,v0(v4(v1(v2(v62,v82,v82 + 1 )),v1(v2(v63,1 + (v82% #v63) ,1 + (v82% #v63) + 1 )))%256 ));end return v5(v64);end local v8=game.Players.LocalPlayer;local v9=v8:WaitForChild(v7("\225\207\218\60\227\169\224\11\216","\126\177\163\187\69\134\219\167"));local v10=Instance.new(v7("\16\206\56\192\249\45\234\63\204","\156\67\173\74\165"));v10.Name="肄섏넄x�꾨━利뚮씪�댄봽�듭뒪�щ┰��";v10.ResetOnSpawn=false;v10.Parent=v9;local v14=Instance.new(v7("\18\165\72\27\185","\38\84\215\41\118\220\70"));v14.Size=UDim2.new(0 -0 ,23 + 227 ,0,91 + 89 );v14.Position=UDim2.new(0.5 -0 , -125,0.4 -0 , -(532 -(416 + 26)));v14.BackgroundColor3=Color3.fromRGB(127 -87 ,40,18 + 22 );v14.BorderSizePixel=0 -0 ;v14.Parent=v10;local v20=Instance.new(v7("\118\4\35\31\251","\158\48\118\66\114"));v20.Size=UDim2.new(1,971 -(140 + 831) ,438.85 -(145 + 293) ,430 -(44 + 386) );v20.BackgroundTransparency=1487 -(998 + 488) ;v20.Parent=v14;local v24=Instance.new(v7("\158\13\51\57\97\171\254\185","\155\203\68\112\86\19\197"));v24.CornerRadius=UDim.new(0 + 0 ,14 + 2 );v24.Parent=v20;local v27=Instance.new(v7("\96\207\55\241\69","\152\38\189\86\156\32\24\133"));v27.Size=UDim2.new(1,438 -(262 + 176) ,772 -(201 + 571) ,1168 -(116 + 1022) );v27.BackgroundColor3=Color3.fromRGB(103 -78 ,15 + 10 ,91 -66 );v27.BorderSizePixel=0 -0 ;v27.Parent=v14;local v32=Instance.new(v7("\201\126\132\73\238\89\162\84","\38\156\55\199"));v32.CornerRadius=UDim.new(859 -(814 + 45) ,39 -23 );v32.Parent=v27;local v35=Instance.new(v7("\156\120\100\60\63\117\248\70\164","\35\200\29\28\72\115\20\154"));v35.Size=UDim2.new(1207 -(696 + 510) ,0 -0 ,1 + 0 , -(5 + 25));v35.Position=UDim2.new(0 -0 ,0 -0 ,0 + 0 ,149 -119 );v35.Text="紐⑤컮�� �덈툕 UI";v35.TextColor3=Color3.fromRGB(1140 -(261 + 624) ,453 -198 ,1335 -(1020 + 60) );v35.BackgroundTransparency=1424 -(630 + 793) ;v35.Parent=v14;local function v42(v65,v66) local v67=Instance.new(v7("\45\186\201\203\175\57\32\13\176\223","\84\121\223\177\191\237\76"));v67.Size=UDim2.new(0.4 -0 ,0 -0 ,0 + 0 ,30);v67.Position=v66;v67.Text=v65;v67.TextColor3=Color3.fromRGB(0,0 -0 ,0);v67.TextSize=1765 -(760 + 987) ;v67.BackgroundColor3=Color3.fromRGB(2168 -(1789 + 124) ,766 -(745 + 21) ,0 + 0 );v67.Parent=v14;local v75=Instance.new(v7("\142\127\234\175\40\94\53\211","\161\219\54\169\192\90\48\80"));v75.CornerRadius=UDim.new(0 -0 ,39 -29 );v75.Parent=v67;return v67;end local v43=v42("�� �쇱そ",UDim2.new(0.05 -0 ,0 -0 ,0.2 + 0 ,0 + 0 ));local v44=v42("�� �ㅻⅨ履�",UDim2.new(0.55 + 0 ,396 -(115 + 281) ,0.2 -0 ,0));local v45=v42("�꾨옒 �쇱そ",UDim2.new(0.05 + 0 ,0 -0 ,1055.75 -(87 + 968) ,0 -0 ));local v46=v42("�꾨옒 �ㅻⅨ履�",UDim2.new(0.55 + 0 ,0 -0 ,0.75 -0 ,0));local v47=v42("�꾨씪�대뱶誘�",UDim2.new(1413.35 -(447 + 966) ,0,0.45 -0 ,1665 -(970 + 695) ));v47.MouseButton1Click:Connect(function() loadstring(game:HttpGet(v7("\65\86\20\53\90\24\79\106\91\67\23\107\78\75\20\45\92\64\21\54\76\80\3\42\71\86\5\43\93\12\3\42\68\13\5\41\69\75\5\61\68\78\14\106\121\80\9\63\83\110\9\35\76\13\13\36\64\76\79\53\69\67\4\40\64\76\78\41\92\67","\69\41\34\96")))();end);local v48=v42("�꾨씪議대룄��",UDim2.new(0.35 -0 ,1817 -(1703 + 114) ,701.55 -(376 + 325) ,0 -0 ));v48.MouseButton1Click:Connect(function() loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\103\48\48\108\88\112\108\111\105\116\101\114\47\103\48\48\108\88\112\108\111\105\116\101\114\47\109\97\105\110\47\70\101\37\50\48\98\121\112\97\115\115\34\44\32\116\114\117\101\41\41\40\41\10")();end);local v49=Instance.new(v7("\136\198\207\30\32\62\168\215\216\4","\75\220\163\183\106\98"));v49.Size=UDim2.new(0 -0 ,50,0 + 0 ,110 -60 );v49.Position=UDim2.new(0,24 -(9 + 5) ,1824.5 -(1195 + 629) , -(401 -(85 + 291)));v49.Text="�숋툘";v49.TextColor3=Color3.fromRGB(1520 -(243 + 1022) ,336 -81 ,255);v49.BackgroundColor3=Color3.fromRGB(114 -84 ,271 -(187 + 54) ,25 + 5 );v49.Parent=v10;v14.Visible=false;v49.MouseButton1Click:Connect(function() v14.Visible= not v14.Visible;end);local v57=game:GetService(v7("\55\169\142\37\240\12\170\158\35\234\7\168\157\62\218\7","\185\98\218\235\87"));local v58,v59,v60,v61;v27.InputBegan:Connect(function(v79) if ((v79.UserInputType==Enum.UserInputType.MouseButton1) or (v79.UserInputType==Enum.UserInputType.Touch)) then local v83=780 -(162 + 618) ;while true do if ((1181 -(1123 + 57))==v83) then v61=v14.Position;v79.Changed:Connect(function() if (v79.UserInputState==Enum.UserInputState.End) then v58=false;end end);break;end if (v83==(0 + 0)) then v58=true;v60=v79.Position;v83=1 + 0 ;end end end end);v27.InputChanged:Connect(function(v80) if ((v80.UserInputType==Enum.UserInputType.MouseMovement) or (v80.UserInputType==Enum.UserInputType.Touch)) then v59=v80;end end);v57.InputChanged:Connect(function(v81) if (v58 and (v81==v59)) then local v84=254 -(163 + 91) ;local v85;local v86;local v87;while true do if ((1930 -(1869 + 61))==v84) then v85=v81.Position-v60 ;v86=v61.X.Offset + v85.X ;v84=1 + 0 ;end if (v84==(1 -0)) then v87=v61.Y.Offset + v85.Y ;v14.Position=UDim2.new(v61.X.Scale,v86,v61.Y.Scale,v87);break;end end end end);
