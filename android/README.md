# Android commons Coding-guidelines


These are the commons classifications used in the sections of my android projects.   
Helpful for have different projects organized in the same way and where many people are modifying the same project
In this other repository are applied these [android-coding-guidelines](https://github.com/Vierco/Get_elements_from_web_and_caching)

## Index

- Android Coding-guidelines    
	- [1. Package structure](#1-package-structure)
	- [2. Views references](#2-views-references)
	- [3. The folder values](#3-folder-values--anim)
	- [4. Dimen resource.xml](#4-dimen-resource)
	- [4.5. Style Resources](#5-style-resources)
 	- [4.6. Dimen Resources](#6-dimen-resources)
 	
 	
### 1. Package structure   
Example of a common android project structure

- vierco.com.guidelines.example (Package_name)       
	- Adapters
	- Activitys
	- Fragments   
	- Methods (these classes contain methods that are repeated throughout the project)   
	- Services
	- Background (contains classes required for certain actions in the project)   

	
### 2. Views references

- Common views       
	- **Button** - btn_view ... findViewById (R.id.BT_name)    
	- **TextView** - txv_view ... findViewById (R.id.TXV_name)    
	- **ToggleButton** - tgb_view ... findViewById (R.id.TGB_name)   
	- **CheckBox** - cb_view ... findViewById (R.id.CB_name)   
	- **CheckedTextView** - ctv_view ... findViewById (R.id.CTV_name)   
	- **ImageView** - imv_view ... findViewById (R.id.IMV_name)   
	- **ImageButton** - imb_view ... findViewById (R.id.IMB_name)   
	- **EditText** - et_view ... findViewById (R.id.ET_name)   
	- **TimePicker** - tpk_view ... findViewById (R.id.TPK_name)   
	- **DataPicker** - dpk_view ... findViewById (R.id.DPK_name)   
	- **ProgressBar** - pbar_view ... findViewById (R.id.PBAR_name)   
	- **SeekBar** - sbar_view ... findViewById (R.id.SBAR_name)   
	- **RadioGroup** - rgroup_view ... findViewById (R.id.RGROUP_name)   
	- **ListView** - listv_view ... findViewById (R.id.LISTV_name)  
	- **ViewPager** - vpager_view ... findViewById (R.id.VPAGER_name) 
	- **GridView** - gridv_view ... findViewById (R.id.gridv_name)  
	- **ScrollView** - scrollv_view ... findViewById (R.id.SCROLLV_name)  
	- **TabWidget** - tabw_view ... findViewById (R.id.TABW_name)  
	- **WebView** - webv_view ... findViewById (R.id.WEBV_name)  
	- **Switch** - switchv_view ... findViewById (R.id.SWITCHV_name)  
	- **RadioGroup** - rgroup_view ... findViewById (R.id.RGROUP_name)  
	
	
- Common Layouts       
	- **LinearLayout** - linearl_view ... findViewById (R.id.LINEARL_name)    
	- **FrameLayout** - framel_view ... findViewById (R.id.FRAMEL_name)    
	- **RelativeLayout** - relativel_view ... findViewById (R.id.RELATIVEL_name)   
	- **Fragment** - fragment_view ... findViewById (R.id.FRAGMENT_name)   




### 3. Folder values & anim  


- res/anim       
	- anim

	
- res/values       
	- strings.xml   
	- arrays.xml   
	- colors.xml   
	- dimen.xml   
	- styles.xml   
	- themes.xml



### 4. Dimen resource


- common padding & margin
	- views_padding  
	- default_text_padding (where appropriate)  
	- title_text_padding   
	- activity_horizontal_margin   
	- activity_vertical_margin   

	
- text sizes       
	- default_text_size   
	- title_text_size     
	- subtitle_text_size   
	- annotations_text_size   
	- action_bar_text_size   
	- button_text_size   






