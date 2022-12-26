- 👋 Hi, I’m @OfficiallyZeus Aka <RA>
- 👀 I’m interested in <curl/Var>...
- 🌱 I’m currently learning <char>..
- 💞️ I’m looking to collaborate on <null/bool>...
- 📫 How to reach me <live/public>...

<!---
OfficiallyZeus/OfficiallyZeus is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Future<RA> updateProfile(UpdateProfileModel data, String token) async {
Map<String, dynamic> profData = {
  "nickname": data.nickname,
  "firstname": data.firstname,
  "lastname": data.lastname,
  "middlename": data.middlename,
  "aboutMe": data.aboutMe,
  "dateOfBirth": data.dateOfBirth,
  "showDateOfBirth": data.showDateOfBirth,
  "gender": data.gender,
  "regionId": data.regionId,
  "telegram": data.telegram,
  "instagram": data.instagram,
  "facebook": data.facebook,
  "linkedin": data.linkedin,
  "picture": data.picture }
