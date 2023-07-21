function varargout = GUI_BEAM_FRP(varargin)
% GUI_BEAM_FRP MATLAB code for GUI_BEAM_FRP.fig
%      GUI_BEAM_FRP, by itself, creates a new GUI_BEAM_FRP or raises the existing
%      singleton*.
%
%      H = GUI_BEAM_FRP returns the handle to a new GUI_BEAM_FRP or the handle to
%      the existing singleton*.
%
%      GUI_BEAM_FRP('CALLBACK',hObject,eventData,handles,...) calls the local
%      function named CALLBACK in GUI_BEAM_FRP.M with the given input arguments.
%
%      GUI_BEAM_FRP('Property','Value',...) creates a new GUI_BEAM_FRP or raises the
%      existing singleton*.  Starting from the left, property value pairs are
%      applied to the GUI before GUI_BEAM_FRP_OpeningFcn gets called.  An
%      unrecognized property name or invalid value makes property application
%      stop.  All inputs are passed to GUI_BEAM_FRP_OpeningFcn via varargin.
%
%      *See GUI Options on GUIDE's Tools menu.  Choose "GUI allows only one
%      instance to run (singleton)".
%
% See also: GUIDE, GUIDATA, GUIHANDLES

% Edit the above text to modify the response to help GUI_BEAM_FRP

% Last Modified by GUIDE v2.5 25-Jun-2023 18:32:07

% Begin initialization code - DO NOT EDIT
gui_Singleton = 1;
gui_State = struct('gui_Name',       mfilename, ...
                   'gui_Singleton',  gui_Singleton, ...
                   'gui_OpeningFcn', @GUI_BEAM_FRP_OpeningFcn, ...
                   'gui_OutputFcn',  @GUI_BEAM_FRP_OutputFcn, ...
                   'gui_LayoutFcn',  [] , ...
                   'gui_Callback',   []);
if nargin && ischar(varargin{1})
    gui_State.gui_Callback = str2func(varargin{1});
end

if nargout
    [varargout{1:nargout}] = gui_mainfcn(gui_State, varargin{:});
else
    gui_mainfcn(gui_State, varargin{:});
end
% End initialization code - DO NOT EDIT


% --- Executes just before GUI_BEAM_FRP is made visible.
function GUI_BEAM_FRP_OpeningFcn(hObject, eventdata, handles, varargin)
% This function has no output args, see OutputFcn.
% hObject    handle to figure
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)
% varargin   command line arguments to GUI_BEAM_FRP (see VARARGIN)

% Choose default command line output for GUI_BEAM_FRP
handles.output = hObject;

% Update handles structure
guidata(hObject, handles);

% UIWAIT makes GUI_BEAM_FRP wait for user response (see UIRESUME)
% uiwait(handles.figure1);


% --- Outputs from this function are returned to the command line.
function varargout = GUI_BEAM_FRP_OutputFcn(hObject, eventdata, handles) 
% varargout  cell array for returning output args (see VARARGOUT);
% hObject    handle to figure
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Get default command line output from handles structure
varargout{1} = handles.output;





function bw_Callback(hObject, eventdata, handles)
% hObject    handle to bw (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of bw as text
%        str2double(get(hObject,'String')) returns contents of bw as a double


% --- Executes during object creation, after setting all properties.
function bw_CreateFcn(hObject, eventdata, handles)
% hObject    handle to bw (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end



function d_Callback(hObject, eventdata, handles)
% hObject    handle to d (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of d as text
%        str2double(get(hObject,'String')) returns contents of d as a double


% --- Executes during object creation, after setting all properties.
function d_CreateFcn(hObject, eventdata, handles)
% hObject    handle to d (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end



function a_d_Callback(hObject, eventdata, handles)
% hObject    handle to a_d (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of a_d as text
%        str2double(get(hObject,'String')) returns contents of a_d as a double


% --- Executes during object creation, after setting all properties.
function a_d_CreateFcn(hObject, eventdata, handles)
% hObject    handle to a_d (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end



function a_Callback(hObject, eventdata, handles)
% hObject    handle to a (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of a as text
%        str2double(get(hObject,'String')) returns contents of a as a double


% --- Executes during object creation, after setting all properties.
function a_CreateFcn(hObject, eventdata, handles)
% hObject    handle to a (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end



function fcly_Callback(hObject, eventdata, handles)
% hObject    handle to fcly (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of fcly as text
%        str2double(get(hObject,'String')) returns contents of fcly as a double


% --- Executes during object creation, after setting all properties.
function fcly_CreateFcn(hObject, eventdata, handles)
% hObject    handle to fcly (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end



function ro_Callback(hObject, eventdata, handles)
% hObject    handle to ro (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of ro as text
%        str2double(get(hObject,'String')) returns contents of ro as a double


% --- Executes during object creation, after setting all properties.
function ro_CreateFcn(hObject, eventdata, handles)
% hObject    handle to ro (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end


function Efl_Callback(hObject, eventdata, handles)
% hObject    handle to Efl (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

% Hints: get(hObject,'String') returns contents of Efl as text
%        str2double(get(hObject,'String')) returns contents of Efl as a double


% --- Executes during object creation, after setting all properties.
function Efl_CreateFcn(hObject, eventdata, handles)
% hObject    handle to Efl (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called

% Hint: edit controls usually have a white background on Windows.
%       See ISPC and COMPUTER.
if ispc && isequal(get(hObject,'BackgroundColor'), get(0,'defaultUicontrolBackgroundColor'))
    set(hObject,'BackgroundColor','white');
end


% % --- Executes during object creation, after setting all properties.
% function ketqua_CreateFcn(hObject, eventdata, handles)
% % hObject    handle to ketqua (see GCBO)
% % eventdata  reserved - to be defined in a future version of MATLAB
% % handles    empty - handles not created until after all CreateFcns called
% set(handles.ketqua,'String',BRANN_ketqua);

% --- Executes on button press in predict.
% --- Executes on button press in predict.
function predict_Callback(hObject, eventdata, handles)
% hObject    handle to predict (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    structure with handles and user data (see GUIDATA)

bw = str2num(get(handles.bw,'String'));
d = str2num(get(handles.d,'String'));
a_d = str2num(get(handles.a_d,'String'));
a = str2num(get(handles.a,'String'));
fcly = str2num(get(handles.fcly,'String'));
ro = str2num(get(handles.ro,'String'));
Efl = str2num(get(handles.Efl,'String'));
%% BR-ANN
load('F:\4. NCKH\2. Cong bo khoa hoc\3. Cong bo 2023\9. RC_FRP beam_303\code\code_BRANN\1. resuilt\w1.mat');
load('F:\4. NCKH\2. Cong bo khoa hoc\3. Cong bo 2023\9. RC_FRP beam_303\code\code_BRANN\1. resuilt\w2.mat');
load('F:\4. NCKH\2. Cong bo khoa hoc\3. Cong bo 2023\9. RC_FRP beam_303\code\code_BRANN\1. resuilt\b1.mat');
load('F:\4. NCKH\2. Cong bo khoa hoc\3. Cong bo 2023\9. RC_FRP beam_303\code\code_BRANN\1. resuilt\b2.mat');
%% ---------------------------------------------------------------------
bw_max = 1854;
d_max = 937;
a_d_max = 8;
a_max = 3050;
fcly_max = 102;
ro_max = 11.46;
Efl_max = 148;
%% ---------------------------------------------------------------------
bw_min = 89;
d_min = 73;
a_d_min = 2.5;
a_min = 300;
fcly_min = 20;
ro_min = 0.11;
Efl_min = 29;
%% data normal
bwn = 2*(bw - bw_min)/(bw_max - bw_min) - 1;
dn = 2*(d - d_min)/(d_max - d_min) - 1;
a_dn = 2*(a_d - a_d_min)/(a_d_max - a_d_min) - 1;
an = 2*(a - a_min)/(a_max - a_min) - 1;
fclyn = 2*(fcly - fcly_min)/(fcly_max - fcly_min) - 1;
ron = 2*(ro - ro_min)/(ro_max - ro_min) - 1;
Efln = 2*(Efl - Efl_min)/(Efl_max - Efl_min) - 1;
%% ---------
inputs = [bwn dn a_dn an fclyn ron Efln];
V_max = 396.3;
V_min = 9.1;
V_n =((b2)+(w2*tansig(b1+w1*inputs')));
BRANN_ketqua = 0.5*(V_n + 1)*(V_max - V_min) + V_min;
set(handles.ketqua,'String',BRANN_ketqua);

% --- Executes during object creation, after setting all properties.
function ketqua_CreateFcn(hObject, eventdata, handles)
% hObject    handle to ketqua (see GCBO)
% eventdata  reserved - to be defined in a future version of MATLAB
% handles    empty - handles not created until after all CreateFcns called
