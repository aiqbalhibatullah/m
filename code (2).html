<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Screening Tuberculosis</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .progress-bar {
            height: 6px;
            transition: width 0.3s ease;
        }
        .tooltip {
            visibility: hidden;
            opacity: 0;
            transition: opacity 0.3s;
        }
        .has-tooltip:hover .tooltip {
            visibility: visible;
            opacity: 1;
        }
    </style>
</head>
<body class="bg-gray-50 min-h-screen">
    <div class="container mx-auto px-4 py-8">
        <div class="bg-white rounded-lg shadow-lg overflow-hidden mb-8">
            <div class="bg-blue-600 px-6 py-4 text-white">
                <div class="flex justify-between items-center">
                    <div>
                        <h1 class="text-2xl font-bold">Screening Tuberculosis</h1>
                        <p class="text-blue-100">Alat skrining awal untuk penilaian risiko TB</p>
                    </div>
                    <button id="adminLogin" class="text-xs bg-white text-blue-600 px-2 py-1 rounded">Login Admin</button>
                </div>
            </div>
            
            <div class="p-6">
                <!-- Form Input Data -->
                <div class="mb-8">
                    <h2 class="text-xl font-semibold mb-4 border-b pb-2">Form Skrining Pasien</h2>
                    <form id="evaluationForm" class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <!-- Patient Identity -->
                        <div class="col-span-2 bg-gray-50 p-4 rounded-lg">
                            <h3 class="font-medium text-gray-800 mb-2">Identitas Pasien</h3>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-1">Nama Lengkap</label>
                                    <input type="text" id="patientName" class="w-full px-3 py-2 border rounded-md" required>
                                </div>
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-1">Umur</label>
                                    <input type="number" id="patientAge" min="1" max="120" class="w-full px-3 py-2 border rounded-md" required>
                                </div>
                                <div class="md:col-span-2">
                                    <label class="block text-sm font-medium text-gray-700 mb-1">Alamat</label>
                                    <textarea id="patientAddress" class="w-full px-3 py-2 border rounded-md" required></textarea>
                                </div>
                                <div>
                                    <label class="block text-sm font-medium text-gray-700 mb-1">Pekerjaan</label>
                                    <input type="text" class="w-full px-3 py-2 border rounded-md">
                                </div>
                            </div>
                        </div>
                        
                        <!-- Main Symptoms -->
                        <div class="col-span-2 bg-blue-50 p-4 rounded-lg">
                            <h3 class="font-medium text-blue-800 mb-2">Gejala Utama</h3>
                            <div class="space-y-3">
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-blue-600 main-symptom" data-weight="3" data-category="Gejala Utama">
                                        <span class="ml-2">Batuk sejak ≥2 minggu</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-blue-600 main-symptom" data-weight="3" data-category="Gejala Utama">
                                        <span class="ml-2">Batuk berdarah</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-blue-600 main-symptom" data-weight="2" data-category="Gejala Utama">
                                        <span class="ml-2">Berat badan turun selama 2 minggu terakhir</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-blue-600 main-symptom" data-weight="2" data-category="Gejala Utama">
                                        <span class="ml-2">Lesu</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Other Symptoms -->
                        <div class="bg-gray-50 p-4 rounded-lg">
                            <h3 class="font-medium text-gray-800 mb-2">Gejala Lain</h3>
                            <div class="space-y-3">
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-gray-600" data-weight="1" data-category="Gejala">
                                        <span class="ml-2">Batuk berdahak</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-gray-600" data-weight="1" data-category="Gejala">
                                        <span class="ml-2">Demam</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-gray-600" data-weight="1" data-category="Gejala">
                                        <span class="ml-2">Keringat di malam hari</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Risk Factors -->
                        <div class="bg-green-50 p-4 rounded-lg">
                            <h3 class="font-medium text-green-800 mb-2">Faktor Risiko</h3>
                            <div class="space-y-3">
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-green-600" data-weight="1" data-category="Faktor Risiko">
                                        <span class="ml-2">Pernah menderita penyakit batuk >3 minggu (TB lama)</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-green-600 risk-factor" data-weight="3" data-category="Faktor Risiko">
                                        <span class="ml-2">Kontak erat dengan pasien TB dalam 3 bulan terakhir</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-green-600" data-weight="-1" data-category="Faktor Risiko">
                                        <span class="ml-2">Pernah vaksinasi BCG</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-green-600" data-weight="1" data-category="Faktor Risiko">
                                        <span class="ml-2">Merokok</span>
                                    </label>
                                </div>
                                <div class="checkbox-group has-tooltip relative">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-green-600" data-weight="-1" data-category="Faktor Risiko">
                                        <span class="ml-2">Cahaya matahari bisa masuk rumah</span>
                                    </label>
                                    <div class="tooltip absolute z-10 w-64 p-2 mt-2 text-sm text-white bg-gray-800 rounded shadow-lg">Jika tidak dicentang → nilai tambah karena ventilasi buruk</div>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Lifestyle -->
                        <div class="bg-purple-50 p-4 rounded-lg">
                            <h3 class="font-medium text-purple-800 mb-2">Gaya Hidup</h3>
                            <div class="space-y-3">
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-purple-600" data-weight="0.5" data-category="Gaya Hidup">
                                        <span class="ml-2">Frekuensi olahraga rendah</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-purple-600" data-weight="0.5" data-category="Gaya Hidup">
                                        <span class="ml-2">Tidak mencuci tangan setiap keluar rumah</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-purple-600" data-weight="0.5" data-category="Gaya Hidup">
                                        <span class="ml-2">Tidak makan sayur dan buah</span>
                                    </label>
                                </div>
                                <div class="checkbox-group">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="form-checkbox h-5 w-5 text-purple-600" data-weight="0.5" data-category="Gaya Hidup">
                                        <span class="ml-2">Tidak memakai masker saat sakit</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                    </form>
                    
                    <div class="mt-6 flex justify-between">
                        <button id="saveBtn" class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-lg flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7H5a2 2 0 00-2 2v9a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-3m-1 4l-3 3m0 0l-3-3m3 3V4" />
                            </svg>
                            Simpan Evaluasi
                        </button>
                        <button id="evaluateBtn" class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-lg flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
                            </svg>
                            Evaluasi Sekarang
                        </button>
                    </div>
                </div>
                
                <!-- Results Section -->
                <div id="resultsSection" class="hidden bg-white rounded-lg border p-6">
                    <h2 class="text-xl font-semibold mb-4 border-b pb-2">Hasil Skrining</h2>
                    
                    <div class="mb-6">
                        <div class="flex justify-between mb-1">
                            <span class="font-medium">Total Skor Evaluasi</span>
                            <span id="totalScore" class="font-bold text-lg">0</span>
                        </div>
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div id="scoreProgress" class="progress-bar bg-blue-600 h-2.5 rounded-full" style="width: 0%"></div>
                        </div>
                        <p id="riskCategory" class="mt-2 text-sm text-gray-600"></p>
                    </div>
                    
                    <div class="text-center py-4">
                        <h3 class="text-lg font-bold" id="tbResult"></h3>
                        <p id="simpleRisk" class="text-sm text-gray-600"></p>
                    </div>
                    <div class="grid md:grid-cols-2 gap-4 hidden" id="adminDetails">
                        <div class="bg-yellow-50 p-4 rounded-lg">
                            <h3 class="font-medium text-yellow-800 mb-3">Rekomendasi</h3>
                            <p id="recommendation" class="text-sm"></p>
                        </div>
                        <div class="bg-blue-50 p-4 rounded-lg">
                            <h3 class="font-medium text-blue-800 mb-3">Rujukan</h3>
                            <p id="referral" class="text-sm">Berdasarkan pedoman TB terbaru</p>
                        </div>
                    </div>
                    
                    <div class="mt-6" id="scoreDetailsContainer">
                        <h3 class="font-medium mb-2">Detail Skor</h3>
                        <div id="scoreDetails" class="text-sm"></div>
                    </div>
                </div>
            </div>
        </div>
        
        =======
    </div>

    <script>
        // Initialize app
        document.addEventListener('DOMContentLoaded', function() {
            document.getElementById('adminLogin').addEventListener('click', checkAdmin);
            // Event listeners  
            document.getElementById('evaluateBtn').addEventListener('click', evaluateTB);
            document.getElementById('saveBtn').addEventListener('click', function() {
            if (!isAdmin) {
                alert("Harus login sebagai admin untuk menyimpan evaluasi.");
                if (checkAdmin()) {
                    saveEvaluation();
                }
            } else {
                saveEvaluation();
            }
        });
            document.getElementById('clearHistory').addEventListener('click', clearAllHistory);
            document.getElementById('searchHistory').addEventListener('input', searchHistory);
        });

        // Check if user is admin (simplified for demo)
        let isAdmin = false;
        
        function checkAdmin() {
            const password = prompt("Masukkan password admin:");
            if (password === "tbadmin123") { // Demo password
                isAdmin = true;
                return true;
            }
            return false;
        }

        // Evaluation function
        function evaluateTB() {
            const form = document.getElementById('evaluationForm');
            const checkboxes = form.querySelectorAll('input[type="checkbox"]:checked');
            
            let totalScore = 0;
            let mainSymptoms = 0;
            let riskFactors = 0;
            let otherScore = 0;
            
            // Categories for details
            const categories = {
                "Gejala Utama": { score: 0, items: [] },
                "Gejala": { score: 0, items: [] },
                "Faktor Risiko": { score: 0, items: [] },
                "Gaya Hidup": { score: 0, items: [] }
            };
            
            checkboxes.forEach(checkbox => {
                const weight = parseFloat(checkbox.dataset.weight);
                const category = checkbox.dataset.category;
                const label = checkbox.parentElement.textContent.trim();
                
                totalScore += weight;
                categories[category].score += weight;
                categories[category].items.push({ label, weight });
                
                if (category === "Gejala Utama") {
                    mainSymptoms += weight;
                } else if (category === "Faktor Risiko") {
                    riskFactors += weight;
                } else {
                    otherScore += weight;
                }
            });
            
            // Update UI
            document.getElementById('totalScore').textContent = totalScore.toFixed(1);
            document.getElementById('scoreProgress').style.width = `${Math.min(100, (totalScore / 15) * 100)}%`;
            
            // Risk assessment
            let riskMessage = "";
            let recommendation = "";
            
            if (mainSymptoms >= 6) {
                riskMessage = "Risiko Tinggi (Diduga TB Aktif)";
                recommendation = "Direkomendasikan untuk dilakukan pemeriksaan dahak (BTA), tes cepat molekuler (TCM), atau rujuk ke fasilitas kesehatan untuk evaluasi lebih lanjut. Prioritaskan pemeriksaan pada pasien dengan gejala batuk berdarah.";
            } else if (totalScore >= 8) {
                riskMessage = "Risiko Sedang (Diduga TB)";
                recommendation = "Disarankan untuk observasi lanjutan selama 2 minggu. Jika gejala menetap atau memburuk, lakukan pemeriksaan penunjang (radiologist atau tes laboratorium). Pertimbangkan faktor risiko kontak erat dengan pasien TB.";
            } else if (totalScore >= 4 && mainSymptoms > 0) {
                riskMessage = "Risiko Rendah (Kemungkinan TB)";
                recommendation = "Observasi gejala selama 1 bulan. Edukasi pasien tentang gejala TB dan kapan harus kembali memeriksakan diri. Pertimbangkan pemeriksaan jika terdapat faktor risiko tambahan.";
            } else {
                riskMessage = "Risiko Sangat Rendah (Tidak Diduga TB)";
                recommendation = "Tidak diperlukan pemeriksaan TB saat ini. Evaluasi penyebab lain dari gejala yang dialami pasien. Tetap monitor jika ada perkembangan gejala.";
            }
            
            document.getElementById('riskCategory').textContent = riskMessage;
            document.getElementById('recommendation').textContent = recommendation;
            
            // Simple public result
            const tbResult = document.getElementById('tbResult');
            if (mainSymptoms >= 6 || totalScore >= 8) {
                tbResult.textContent = "Terindikasi TB";
                tbResult.className = 'text-lg font-bold text-red-600';
            } else {
                tbResult.textContent = "Tidak Terindikasi TB"; 
                tbResult.className = 'text-lg font-bold text-green-600';
            }
            document.getElementById('simpleRisk').textContent = riskMessage;
            
            // Admin-only details
            document.getElementById('adminDetails').style.display = isAdmin ? 'grid' : 'none';
            
            // Score details
            let detailsHTML = '';
            for (const [category, data] of Object.entries(categories)) {
                if (data.items.length > 0) {
                    detailsHTML += `<div class="mb-3">
                        <h4 class="font-medium mb-1">${category}: ${data.score.toFixed(1)} poin</h4>
                        <ul class="list-disc list-inside text-xs">`;
                    
                    data.items.forEach(item => {
                        detailsHTML += `<li>${item.label} (${item.weight > 0 ? '+' : ''}${item.weight} poin)</li>`;
                    });
                    
                    detailsHTML += `</ul></div>`;
                }
            }
            
            document.getElementById('scoreDetails').innerHTML = detailsHTML;
            
            // Show/hide admin-only details
            const detailsContainer = document.getElementById('scoreDetailsContainer');
            detailsContainer.style.display = isAdmin ? 'block' : 'none';

            // Show results
            document.getElementById('resultsSection').classList.remove('hidden');
        }

        // Save evaluation to localStorage
        function saveEvaluation() {
            if (!document.getElementById('resultsSection').classList.contains('hidden')) {
                const form = document.getElementById('evaluationForm');
                const checkboxes = form.querySelectorAll('input[type="checkbox"]:checked');
                
                const evaluation = {
                    date: new Date().toISOString(),
                    patientName: document.querySelector('#evaluationForm input[type="text"]').value,
                    patientAge: document.querySelector('#evaluationForm input[type="number"]').value,
                    patientAddress: document.querySelector('#evaluationForm textarea').value,
                    patientJob: document.querySelectorAll('#evaluationForm input[type="text"]')[1].value,
                    totalScore: document.getElementById('totalScore').textContent,
                    riskCategory: document.getElementById('riskCategory').textContent,
                    items: []
                };
                
                checkboxes.forEach(checkbox => {
                    evaluation.items.push({
                        label: checkbox.parentElement.textContent.trim(),
                        weight: parseFloat(checkbox.dataset.weight),
                        category: checkbox.dataset.category
                    });
                });
                
                // Get existing history or initialize empty array
                let history = JSON.parse(localStorage.getItem('tbEvaluations')) || [];
                
                // Add new evaluation
                history.unshift(evaluation);
                
                // Save to localStorage
                localStorage.setItem('tbEvaluations', JSON.stringify(history));
                
                // Update UI
                loadHistory();
                
                // Notification
                alert('Evaluasi telah disimpan ke riwayat!');
            } else {
                alert('Silakan evaluasi terlebih dahulu sebelum menyimpan!');
            }
        }

        // Load saved evaluations from localStorage
        function loadHistory() {
            const history = JSON.parse(localStorage.getItem('tbEvaluations')) || [];
            const historyList = document.getElementById('historyList');
            
            if (history.length === 0) {
                historyList.innerHTML = '<p class="text-center text-gray-500 py-4">Tidak ada riwayat evaluasi yang tersimpan</p>';
                return;
            }
            
            let historyHTML = '';
            
            history.forEach((eval, index) => {
                const date = new Date(eval.date);
                const dateStr = date.toLocaleDateString('id-ID', {
                    day: 'numeric', 
                    month: 'long', 
                    year: 'numeric',
                    hour: '2-digit',
                    minute: '2-digit'
                });
                
                historyHTML += `
                    <div class="border rounded-lg p-4 hover:bg-gray-50">
                        <div class="flex justify-between items-start mb-2">
                            <div>
                                <h3 class="font-medium">Evaluasi ${index + 1}</h3>
                                <p class="text-xs text-gray-500">${dateStr}</p>
                            </div>
                            <div class="flex items-center">
                                <span class="font-bold mr-2">${eval.totalScore}</span>
                                <span class="text-xs px-2 py-1 rounded-full ${getRiskColor(eval.riskCategory)}">${eval.riskCategory}</span>
                            </div>
                        </div>
                        <div class="text-sm text-gray-600 mt-1">${eval.items.length} item terpilih</div>
                        <button class="deleteBtn mt-2 text-xs text-red-600 hover:text-red-800" data-index="${index}">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 inline mr-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16" />
                            </svg>
                            Hapus
                        </button>
                    </div>
                `;
            });
            
            historyList.innerHTML = historyHTML;
            
            // Add event listeners to delete buttons
            document.querySelectorAll('.deleteBtn').forEach(btn => {
                btn.addEventListener('click', function() {
                    deleteEvaluation(parseInt(this.dataset.index));
                });
            });
        }

        // Delete single evaluation
        function deleteEvaluation(index) {
            if (confirm('Apakah Anda yakin ingin menghapus evaluasi ini?')) {
                let history = JSON.parse(localStorage.getItem('tbEvaluations')) || [];
                history.splice(index, 1);
                localStorage.setItem('tbEvaluations', JSON.stringify(history));
                loadHistory();
            }
        }

        // Clear all history
        function clearAllHistory() {
            if (confirm('Apakah Anda yakin ingin menghapus semua riwayat evaluasi?')) {
                localStorage.removeItem('tbEvaluations');
                loadHistory();
            }
        }

        // Search history
        function searchHistory() {
            const searchTerm = this.value.toLowerCase();
            const evaluations = document.querySelectorAll('#historyList > div');
            
            evaluations.forEach(eval => {
                const text = eval.textContent.toLowerCase();
                eval.style.display = text.includes(searchTerm) ? 'block' : 'none';
            });
        }

        // Helper function for risk category color
        function getRiskColor(category) {
            if (category.includes("Tinggi")) return "bg-red-100 text-red-800";
            if (category.includes("Sedang")) return "bg-yellow-100 text-yellow-800";
            if (category.includes("Rendah")) return "bg-green-100 text-green-800";
            return "bg-gray-100 text-gray-800";
        }
    </script>
</body>
</html>
