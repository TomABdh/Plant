# Plant
<已完成
# 在媒体商店(图库)中将图像添加到相册中。
     
# 使用静态变量或单例模式创建全局变量，在不同的类之间共享数据。在发送方类中，将数据存储在全局变量中.
     
# 在接收方类中，从全局变量中获取数据./>
<未完成
 # E/BitmapFactory: Unable to decode stream: java.io.FileNotFoundException: /external_files/202303012313.jpg: open failed: ENOENT (No such file or directory)
 # channel 'ccad12c Application Error: com.example.plant (client)' ~ receive message failed, errno=11, seq = 128942
 />
 <To do list
     检查文件是否存在于/external_files/目录下，如果不存在，则可能需要恢复文件或者更新应用程序。
     检查应用程序是否有访问/external_files/目录的权限。您可以在应用程序的AndroidManifest.xml文件中添加以下权限： <uses-permission                 android:name="android.permission.READ_EXTERNAL_STORAGE"/>
     检查文件名和路径是否正确。可以尝试使用正确的文件名和路径重新加载文件。
     如果问题仍然存在，请检查其他可能导致问题的原因，例如文件格式不受支持或磁盘空间不足等。
 />
